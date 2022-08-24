# SIMPLE API WITH DJANGO REST FRAMEWORK
[Django REST framework](http://www.django-rest-framework.org/) is a powerful and easy toolkit for building Web APIs.

## Requirements
- Python 3.8
- Django 4.0
- Django REST Framework
- Other libraries you can read on requirements.txt

## Installation
After you cloned the repository, you want to create a virtual environment, so you have a clean python installation.
You can do this by running the command
```
python -m venv env
```

After this, it is necessary to activate the virtual environment, you can get more information about this [here](https://docs.python.org/3/tutorial/venv.html)

You can install all the required dependencies by running
```
pip install -r requirements.txt
```

## Structure
In a RESTful API, endpoints (URLs) define the structure of the API and how end users access data from our application using the HTTP methods - GET, POST, DELETE. Endpoints should be logically organized around _collections_ and _elements_, both of which are resources.



Endpoint |HTTP Method | CRUD Method | Result
-- | -- |-- |--
`product-list` | GET | READ | Get all product
`product-detail/:id` | GET | READ | Get a single product
`product-list`| POST | CREATE | Create a new product
`product-create/:id` | PUT | UPDATE | Update a product
`product-delete/:id` | DELETE | DELETE | Delete a product

## Use
We can test the API using  [Postman](https://www.postman.com/)



Before we jumped-in into web server you have to run the desired server
```
python manage.py runserver
```


## Contributing
Pull requests are very welcome.

