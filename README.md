REST API для проекта Yatube
## Описание проекта
Проект представляет собой REST API для социальной сети для публикации личных дневников.
Более подробно описание проекта представлено в https://github.com/dimn3/api_final_yatube#readme
В данном проекте REST API для проекта реализован следующий функционал:
* Получение списка публикаций или отдельной публикации по id.
* Просмотр, создание, удаление и изменение записей (публикаций).
* Получение всех комментариев к публикации или комментария к публикации по id.
* Просмотр, создание, удаление и изменение комментариев.
* Просмотр и создание групп (сообществ).
* Получение списка доступных сообществ и получение информации о сообществе по id.
* Подписка на пользователей.
* Авторизация по JWT (JSON Web Token) токену.
* Регистрация пользователей и управление правами доступа.
## Используемые технологии
* Python 3.7
* Django 2.2
* Django Rest Framework 3.12
* Postman
* Simple-JWT 4.7.2
## Установка проекта
Клонируйте данный репозиторий на свой компьютер и перейдите в папку проекта.
<pre><code>git clone https://github.com/dimn3/api_final_yatube</code>
<code>cd api_final_yatube</code></pre>
Создайте и активируйте виртуальное окружение:
<pre><code>python -m venv venv</code>
<code>source venv/Scripts/activate  #для Windows</code>
<code>source env/bin/activate       #для Linux и macOS</code></pre>
Установите требуемые зависимости:
<pre><code>pip install -r requirements.txt</code></pre>
Примените миграции:
<pre><code>python manage.py migrate</code></pre>
Запустите django-сервер:
<pre><code>python manage.py runserver</code></pre>
## Документирование API
Структура запросов и ответов API документирована в ReDoc.
После запуска проекта документация доступна по адресу http://localhost:8000/redoc/
