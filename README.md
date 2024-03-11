# Django-FoodMenu

To run the server:

1. Navigate to food_menu folder
2. Run command in terminal : python manage.py runserver
3. The developement server would usually be at : http://127.0.0.1:8000/
   if not, it will be mentioned in the terminal

# Extra INFO

To create an app : django-admin startproject <my_site>

A django app consists of individual applications
To create an application : pytho manage.py startapp <app_name>

To make database table : python manage.py migrate

If made changes in models specify the app when migrating
To migrate and tell changes : python manage.py makemigrations <app_name>
it will create a model like app_name/migrations/0001_initial.py
To create database model : python manage.py sqlmigrate <app_name> 0001

To work in python shell : python manage.py shell

To create super-user : python manage.py createsuperuser
To view the Items table in admin panel register it in admin.py : admin.site.register(Item)
