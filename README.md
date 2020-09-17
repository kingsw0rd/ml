# Deploying Machine Learning using Django

## First of all install the requirements to run the project.
```
pip install -r requirements.txt
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
## Run Web Browser

```
http://127.0.0.1:8000/api/v1/
```
