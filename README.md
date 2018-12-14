# django-simple-project-layout

Basic Django layout for web applications based on good practice from the book "Two Scoops of Django 1.11"

The easiest way to rename the project is to open in in Pycharm and use Rename option (Shift+F6) on project folder, 
with option 'Search for references'.

## Setup

First activate you virtual environment with Python 3.6+ installed, then:

```
pip install -r requirements/[local, production].txt
export DJANGO_SETTINGS_MODULE=school.settings.[local, production]
```

## Run application directly

* Django server
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```
