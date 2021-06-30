# CREATING_DJANGO_API_WORKFLOW

## Notes

```
  $ python3 -m venv env
  $ source env/bin/activate
  $ pip install django djangorestframework pylint pylint-django
  $ django-admin startproject main .
  $ python3 manage.py startapp api

  # update api/settings.py with:
  # create your models
  # create your serializers
  # update admin.py so the entities are visible in admin.

  $ python3 manage.py makemigrations
  $ python3 manage.py migrate
  $ python3 manage.py createsuperuser
  $ python3 manage.py runserver

  # then , build your views, urls, auth, etc
```
