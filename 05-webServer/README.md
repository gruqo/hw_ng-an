<h2> ДЗ по теме № 05 - Angie как веб-сервер </h2>

<br>

<h3> 1. Подготовка </h3>

Angie запущен в docker-контейнере от имени непривилегированного пользователя

![Скрин](images/docker_status.png)

<br>
Страница доступна по адресам:

|Назначение|Ссылка|
|:---|:----|
|Основная|http://hw.practicum-demo.space|
|Проверка редиректа| http://test.practicum-demo.space|

<br>


<h3> 2. Выполненная работа </h3>

Редирект с test.* на hw.*  
![Скрин](images/remote_redirect.png)
<br>

Открытая страница hw.* в веб-браузере  
![Скрин](images/page.png)
<br>

Перенаправление с /images на /images/  
Ошибка 404 связана с отсутствующим index.html (если нет index файла - возвращаем 404 вместо 403)  
![Скрин](images/page_sl.png)
<br>
