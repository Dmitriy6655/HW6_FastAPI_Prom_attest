Инструкция:

1) создайте виртуальное окружение (ВО)

2) запустите ВО

3) для добавления нужных библиотек python в виртуальное окружение наберите команду:

>pip freeze > requirements.txt

4) установим веб-сервер при помощи команды:

>pip install uvicorn[standard]

Uvicorn — это реализация веб-сервера ASGI для Python.
   
5) cоздайте в корне директории файл .env со следующим содержимым:


>DATABASE_URL=sqlite:///database.db


6) запустите файл main.py при помощи следующей команды:


>uvicorn main:app --reload


7) перейдите в браузере по адресу :

> http://127.0.0.1:8000/docs

8) заполните БД
