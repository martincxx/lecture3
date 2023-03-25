# Django

## Prerequisites

* Python3
* Pip

## Installation

```
pip3 install Django
```

Be sure to add django-admin to your $PATH

## Create a Django Project

A Django Project may contain one or more Django Apps

```
django-admin startproject lecture3
```

Where lecture is our project name.

## Add your first Django App

Now, we can add a first Django App

```
python3 manage.py startapp hello
```

Our first app is named hello, and it will be the equivalent of a Hello World! on Django.

A new hello directory is created in our lecture3 directory

## Install (Add) this App

Go to our project's `settings.py` and add hello to the INSTALLED_APPS list.

Now, we can proceed with [views](views.md)
