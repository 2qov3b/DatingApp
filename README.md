# DatingApp

## Environment settings 
Let's start a virtual environment:
```
python3 -m venv env
source env/bin/activate

pip install django
django-admin startproject datingapp .
django-admin startapp main
python manage.py makemigrations main
```