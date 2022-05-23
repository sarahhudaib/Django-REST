# Django REST Framework / Docker
Author: Sarah Hudaib

# Challenge
Use Django REST Framework to create an API, then “containerize” it with Docker.

# Architecture
- Python 3.9.5 
- Django 4.0.4
- Docker 20.10.12

# Try it out by installing the requirements. (Works only with python >= 3.8, due to Django 4)
```
# Djang
$ pip install django
pip install django_rest_framework

# env
$ python -m venv django_env
$ source ./django_env/bin/activate

# requirements
$ pip freeze > requirements.txt
```
install docker
```
sudo apt-get update
sudo apt-get upgrade
sudo apt install docker.io
systemctl start docker
systemctl enable docker
docker --version
```

# Run the Project
Open Console in Main Project Directory.

- $ git clone git@github.com:sarahhudaib/Django-REST.git
- $ cd Django-REST
- $ python manage.py runserver
- on your browser (http://127.0.0.1:8000/todos/api) 
- OR this link to navigate http://127.0.0.1:8000/todos/api/2
