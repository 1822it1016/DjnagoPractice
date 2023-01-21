CREATE  A PROJECT
->  django-admin startproject <projectname>

RUNSERVER 
->  python manage.py runserver

CREATE A SUPER USER
->  python manage.py createsuperuser

CREATE  A NEW APP
->  python manage.py startapp <appname>


CREATION OF TABLE 
->  python manage.py makemigrations     // staging step
->  python manage.py migrate            // table will get created


#if you have models(table in db) 
models <-> views <-> html

#without model
views -> html
