# multistack-conhecendo-django

## 1 - Criar um projeto Django: 
Criar um projeto no Pycharm (Pure Python) junto com a Virtualenv. 
Ir em files > settings > Python interpreter e instalar o Django.
No terminal, com a (venv) ativa digitar: django-admin startproject nivelamento_django

## 2 - Criar uma aplicação: 
Digite ls e veja o nome do projeto (nivelamento_django) e a venv. 
Digite cd nivelamento_django e dentro da pasta digite: python manage.py startapp app  

## 3 - Executando Projeto: 
No terminal e dentro da pasta do projeto digite: python manage.py runserver. Deve aparecer: http://127.0.0.1:8000/
