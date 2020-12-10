# Django project - Blog


### Creating venv
```
python -m venv venv
```
```
.\venv\Scripts\activate
```
____
### Installing Django
```
pip install Django
```
____
### Creating project
```
django-admin startproject siteblog
```
____
### Creating new app - SiteBlog
```
python manage.py startapp siteblog
```
____
### Static files
```
python manage.py collectstatic
```
_____
### Creating DB
```
python manage.py makemigrations
```
```
python manage.py migrate
```
_____
### Create admin
```
python manage.py createsuperuser
```
_____
### Debug in admin
https://django-debug-toolbar.readthedocs.io/en/latest/installation.html
_____
### ckEditor
https://pypi.org/project/django-ckeditor-5/
