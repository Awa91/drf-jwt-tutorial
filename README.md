<p align="center">
    <img src=".github/public/drf-logo.jpg" alt="Logo Django REST Framework" width="440"/>
</p>

# JWT Authentication in Django project

This repository is a minimal example of JWT authentication implementation in the Django REST framework.

## Technologies

 - Python 3
 - Django 5
 - Django REST Framework

## Getting started

Create a new Python virtual environment
```shell
python -m venv .venv
```

Activate the virtual environment
```shell
source .venv/bin/activate
```

Install required packages
```shell
python -m pip install -r requirements.txt
```

Run Django server
```shell
python manage.py runserver
```


Task 1 drf-jwt
cd drf_projects
cd drf-jwt-tutorial
py -m venv .venv
.venv\scripts\activate
py -m pip install django  djangorestframework djangorestframework-simplejwt dj-rest-auth
py manage.py createsuperuser

superuser = admin
psw 12345
