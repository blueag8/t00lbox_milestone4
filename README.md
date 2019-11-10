# Code Institute

creat env variable
python3 -p venv
source bin/activate
easy_install django==1.11.24
django-admin startproject "" .
python3 manage.py runserver
python3 manage.py migrate
django-admin startapp ""
python3 manage.py createsuperuser
