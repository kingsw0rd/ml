# Deploying Machine Learning using Django

## First of all install the requirements to run the project.
```
pip freeze > requirements.txt
```
## To Run Django Project

```
git clone https://github.com/kingsw0rd/ml-django.git
cd ml-django/backend/server

python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
