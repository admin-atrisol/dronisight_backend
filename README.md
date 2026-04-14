# dronisight_backend
Dronisight is the project for powerline inspection using drones for fault detections using AI
versions  Python==3.14.4
Django==5.2.13


django-admin startproject dronisight

cd dronisight

python manage.py startapp powerlines

add 'powerlines',   in settings.py

add urls.py file in powerlines app directory

add path("powerlines/", include("powerlines.urls")),   in main project urls.py file


python manage.py startapp users

add 'users',   in settings.py

add urls.py file in users app directory

add path("users/", include("users.urls")),   in main project urls.py file

