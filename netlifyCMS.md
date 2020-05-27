# Админ панель Netlify CMS `редактирование контента вебсайта`

------

Доступ к административной панели  `Host + /admin/#`

### Host Netlify => [https://sparkybit.netlify.app/](https://sparkybit.netlify.app/)

### Host Sparkybit => [https://sparkybit.com/](https://sparkybit.com/)

`Host Netlify` выдан системой Netlify и являеться основным. `Host Sparkybit`  на данный момент проксируеться через `Host Netlify` 

Это важно для понимания, что `Host Sparkybit` используеться для доступа к вебсайту для получения контента. `Host Netlify` для входа в админ панель редактирования кнтента. 

```
! Если при работе с админ панелью вас перенаправило на Host Sparkybit нужно исправить на Host Netlify или перезайти на Host Netlify. В противном случае Netlify CMS будет обращаться по неверному API 

```

Доменные имена настраиваються в админ панели Netlify => [Netlify.md](C:\Users\Admin\OneDrive\Desktop\manual\netlify.md)

## URL доступа к админ панели Netlify [https://sparkybit.netlify.app/admin/#](https://sparkybit.netlify.app/admin/#)

![](https://github.com/AndrewSchastlivcev/Netlify-doc/blob/master/images/login_admin.png)

![](images\login_admin.png)

![](https://github.com/AndrewSchastlivcev/Netlify-doc/blob/master/images/login_admin2.png)

![](.\images\Login_admin2.png)

1. Регистрация нового пользователя 
2. Вход используя учетные данные пользователя  которые храняться в  в админ панели Netlify => [Netlify.md](C:\Users\Admin\OneDrive\Desktop\manual\netlify.md)
3. Запрос сброса пароля

![](https://github.com/AndrewSchastlivcev/Netlify-doc/blob/master/images/editor.png)

![](.\images\editor.png)

1. Переход к быстрому добавлению вакансии / статьи в блог

2. Переход к содержимому контента 

3. Переход к содержимому медиа

4. Категории контента расположенного на вебсайте. 

   `Careers` + ` Blog` Динамически измениямый контент, каждая новая вакансия или статья добавляет новую страницу

   `Pages` Статические страницы - контент основных страниц вебсайта, их колличество не изменяеться в редакторе 

![](https://github.com/AndrewSchastlivcev/Netlify-doc/blob/master/images/pages.png)

![](.\images\pages.png)

![](https://github.com/AndrewSchastlivcev/Netlify-doc/blob/master/images/content.png)

![](.\images\content.png)

1. В этом разделе находяться все поля которые нужно заполнить для редактирования / создания новой страницы

2. Предпросмотр страницы. Показывает изменения сразу после изменения контента. Предварительный просмотр страницы после деплоя вебсайт

3. Кнопка сохранения изменений. После нажатия запускаеться деплой вебсайта, результат будет доступен по истечению примерно 5 минут 

   ### Host Netlify => [https://sparkybit.netlify.app/](https://sparkybit.netlify.app/)

   ### Host Sparkybit => [https://sparkybit.com/]

   ```
   Структура всех полей для редактирования страниц изменяться только разработчиком
   ```

   
