# django 4.2 empty project

Project bootstrap with django 4.2
 
 - Rename file .env-example to .env and fill with your information

Crear enviroment

    python3 -m venv venv

    windows
        .\venv\Scripts\activate

Install requirements:

    pip install -r requirements.txt

Apply migrations

    python manage.py migrate

Create user

    python manage.py createsuperuser

Run project

    python manage.py runserver

