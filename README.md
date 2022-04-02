# django-react
Тестовый проект с использованием django и react.js

# Getting Started

Клонировать репозиторий:<br> 
### `git clone git@github.com:avramenkomy/django-react.git`
<br><br>

Перейти в папку проекта:<br>
### `cd django-react/django_react`
<br><br>

Создать виртуальное окружение:<br>
### `python3 -m venv venv`
<br><br>

Активировать виртуальное окружение:<br>
### `source venv/bin/activate` - для mac os/linux
### `venv\scripts\activate.bat` - для windows
<br><br>

Установить зависимости:<br>
### `pip3 install -r requirements.txt`
<br><br>

Создать и проверсти миграцию БД:<br>
### `python3 manage.py makemigrations`
### `python manage.py migrate`
<br><br>

Запустить сервер Django:<br>
### `python3 manage.py runserver`
<br><br>

Создать записи в БД с помощью API django rest framework:<br>
### `http://127.0.0.1:8000/api/lead/`
#### поле name: `test user 1`
#### поле email: `test1@example.com`
#### поле message: `test message from user 1`
Сделать POST запрос на сохранение записи
#### поле name: `test user 2`
#### поле email: `test2@example.com`
#### поле message: `test message from user 2`
Сделать POST запрос на сохранение записи
<br><br>

Запустить сервер React frontend:<br>
### `cd frontend && npm run dev`
<br><br>

Перейти в браузер и главной странице увидеть результат:<br>
### `http://127.0.0.1:8000/`
