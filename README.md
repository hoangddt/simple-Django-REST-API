# Simple Django REST framework
-----------

This is a simple web-app that implement django-rest-framework  This is created by hoangddt and follow this instruction [REST framework tutorial](http://www.django-rest-framework.org/tutorial/1-serialization/)
-----------

## Run

### Setting up a new enviroment
```sh
virtualenv env
source env/bin/activate
```

Then install dependencies
```sh
pip install django
pip install djangorestframework
pip install pygments  # We'll be using this for the code highlighting
pip install django-rest-swagger
```
### Run the app
```sh
cd simple-Django-REST-API
```
Now we syncdb for the first time
```sh
python manage.py migrate
python manage.py createsuperuser
```

And then Run server
```sh
python manage.py runserver
```
And then go ahead at http://localhost:8000/

### Browser API
You can go to /docs to see the API and test
