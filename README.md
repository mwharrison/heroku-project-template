# Heroku Django 3 Starter Template
A template to get up and running on Heroku with Django 3 and Python 3.9

# How to setup
1. Create your virtual environment
2. Install Django (`pip install django`)
3. `django-admin startproject --template https://github.com/mwharrison/heroku-project-template/archive/main.zip <project_name>`

# How to deploy
```
$ git init
$ git add -A
$ git commit -m "initial commit"

$ heroku create
$ git push heroku master
```
