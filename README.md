# Django

## History

Django is a high-level Python web framework that encourages rapid development and clean, pragmatic design. It was first released in 2005 and is maintained by the Django Software Foundation (DSF).

## Features

- Admin interface
- Authentication
- URL routing
- Template engine
- Object-relational mapping (ORM)

## Advantages

- Rapid development
- Security features
- Scalability
- Community support

## Websites using Django

- Instagram
- Pinterest
- The Washington Times

# Let's get Started
To start a project
```sh
django-admin startproject myapp
```
> [!TIP]
> Add preiod (.) to not create new folder for it.
Some before config on app:
```python
ALLOWED_HOSTS = ['*']
TIME_ZONE = 'Asia/Dhaka'
CSRF_TRUSTED_ORIGINS = ['<domain name>']
```

# Database command
follow only three steps
- Change your models (in models.py).
- Run `python manage.py makemigrations` to create migrations for those changes
- Run `python manage.py migrate to apply` those changes to the database.

# To create super user
```sh
python manage.py createsuperuser
```


