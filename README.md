# django-api-demo

# Prepare environment
```shell script
$ python3 -m venv .venv
$ source .venv/bin/activate
```

# Installing dependencies
```shell script
$ pip3 install django
$ pip3 install djangorestframework
```

## Creating Django project

```shell script
$ django-admin startproject <project_name>
$ pip3 freeze > requirements.txt # used for creating a requirements.txt file
$ python3 manage.py migrate
$ python3 manage.py createsuperuser
```

## Running server

```shell script
$ python3 manage.py createsuperuser
```

You will see something like this:
```shell script
Watching for file changes with StatReloader
Performing system checks...

System check identified no issues (0 silenced).
September 17, 2020 - 04:28:49
Django version 3.1.1, using settings 'djangoapidemo.settings'
Starting development server at http://127.0.0.1:8000/
Quit the server with CONTROL-C.

```