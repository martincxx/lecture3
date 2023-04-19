# Summary of Commands and other tricks

## Create a python environment

python3 -m venv .venv
source .venv/bin/activate

## Select interpreter

`ctrl+shift+p`

## Update pip and install django

```
python3 -m pip install --upgrade pip
python3 -m pip install django
```

## Create a gitignore

`https://www.toptal.com/developers/gitignore`

## Create a django project

`django-admin startproject web_project .`

## Create an empty dev db

`python3 manage.py migrate`

## Create a django app

```python3 manage.py startapp hello

python3 manage.py runserver
```

## After changing the model run

```
python manage.py makemigrations

python manage.py migrate

```

## create requirements.txt

`pip freeze > requirements.txt`

## Create superuser

```
python3 manage.py createsuperuser --username=djangoadmin --email=martin_fcf@yahoo.es

pass:\*\*\*\*\*

```

## Django administration => login

`http://127.0.0.1:8000/admin`

## exit/close .venv

`deactivate`

## Containerize the app

```
//TODO
```
