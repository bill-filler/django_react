# django_react
This demonstrates how to render React component from a django template using django-webpack-loader.
Based on https://blog.botreetechnologies.com/django-with-reactjs-b8da6f95171f

Steps to install:
1. Clone repo
1. cd root directory
1. create virtualenv for python3
1. ```pip install django==1.11.10```
1. ```pip install django-webpack-loader```
1. ```npm install```
1. To build the js bundle ```./node_modules/.bin/webpack -d```
1. Start python server: ```python manage.py runserver```
1. To auto watch/build assets ```./node_modules/.bin/webpack --config webpack.config.js --watch```. This will be when changes are made in ```assets/js``` directory
1. To see React rendered: ```http://127.0.0.1:8000/react/```
