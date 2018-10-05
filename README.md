# django-cheatsheet

## How to create a new Django project
```bash
django-admin startproject projectname
```
## How to start the Django development server
```bash
python3 manage.py runserver
```
## But how do I stop it?
```bash
ctrl + C
```
## How to create a new application in the project
```bash
python3 manage.py startapp main_app
```
## Django Directory Structure
```
djangoproject
|
|- djangoproject
|  |
|  |- settings.py: Main settings for project (database/apps/config/etc..)
|  |- urls.py: Main URLs for entire project
|
|- application_name
|  |- static: (directory) Holds all static files (CSS/JS/img/ aux.forms..)
|  |- templates: (directory) Holds all HTML template files
|  |- migrations: (directory) This holds all data migration files
|  |- admin.py: This is where we register data models
|  |- models.py: This is where we put all data models
|  |- views.py: This is where we put the functions that run our routes
|  |- urls.py: Every URL for our site is defined here
|
|- manage.py: Let's us manage everything about our project
```
