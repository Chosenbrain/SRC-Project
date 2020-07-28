
- Django 3.0.x
- [django-allauth](https://github.com/pennersr/django-allauth) for user registration
- [Bootstrap v4](https://github.com/twbs/bootstrap) for styling
- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar) for debugging
- [django-crispy-forms](https://github.com/django-crispy-forms/django-crispy-forms) for DRY forms

## 📖 Install

```
$ git clone git@github.com:diek/e_HealthCare.git.git  
$ cd e_HealthCare  
$ pip install -R requirements.txt  

# Run Migrations
(djangox) $ python manage.py migrate

# Create a Superuser:
(djangox) $ python manage.py createsuperuser

# Confirm everything is working:
(djangox) $ python manage.py runserver

# Load the site at http://127.0.0.1:8000
```


# Create PostgreSQL database and database user
`CREATE DATABASE e_HealthCare;`  
`CREATE USER ehc_appuser WITH PASSWORD 'secure_password';`  
`ALTER ROLE ehc_appuser SET client_encoding TO 'utf8';`  
`ALTER ROLE ehc_appuser SET default_transaction_isolation TO 'read committed';`  
`ALTER ROLE ehc_appuser SET timezone TO 'UTC';`  

`GRANT ALL PRIVILEGES ON DATABASE e_HealthCare TO ehc_appuser;`
# SRC-Project
