# Django - Setup and Basic Models

This assignment is designed to help you practice setting up a Django project, connecting it to a PostgreSQL database, and creating a basic model.

In this assignment, you will be required to:

1. Set up a virtual environment.
2. Install Django and the required dependencies.
3. Connect PostgreSQL to Django.
4. Create a Django model for the "Student" entity.

## Virtual Environment Setup

- Create and activate a Python Virtual Environment where you can install your project dependencies.

## Django and psycopg3 Installation

Once your virtual environment is up and running, you need to install Django and psycopg2. Here's how:

- Install Django onto your `venv`
- Install the `"psycopg[binary]"` library to enable PostgreSQL support in Django

## Connecting PostgreSQL to Django

Next, you need to connect PostgreSQL to Django. Follow these steps:

- Locate the `settings.py` file within your Django project.
- In the `DATABASES` section, connect PostgreSQL to Django

## Creating the Student Model

The final step is to create the `Student` model within your Django project. Here's what you need to do:

- Locate the `models.py` file within your app (usually located in the app's directory).
- Define the `Customer` model with the required fields (first_name:char/last_name:char/account_type):

```bash
class Customer(models.Model):
    pass
```

- Now makemigrations and migrate onto your postgresdb

## Further Resources

If you need further assistance or would like to explore more about Django, consider referring to the following resources:

- Django Official Documentation: [https://docs.djangoproject.com/](https://docs.djangoproject.com/)
- Django Models Documentation: [https://docs.djangoproject.com/en/3.2/topics/db/models/](https://docs.djangoproject.com/en/3.2/topics/db/models/)
