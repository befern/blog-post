# Blog Post

Blog Post created in Python with Django Framework.

## Description

A personal blog post made with Django. It allows registered users to make posts, 
save them as drafts and publish then automatically or at scheduled times.
Visitors can view and comment posts.
Only approved comments will be shown in the main page.

Django admin can be used to manage users.


## Getting Started

These instructions will get you a copy of the project up and running 
on your local machine for development and testing purposes.

### Prerequisites

Python3


### Installing

For development purposes is recommended to create a virtual environment.
On the repository folder create a virtual environment called myvenv 
(myvenv folder is already on the gitignore file)

Linux and OSX
```
python3 -m venv myvenv
```

Windows
```
python -m venv myvenv
```


#### Execute the virtual environment

Linux and OSX
```
source myvenv/bin/activate
```

Windows
```
myvenv\Scripts\activate
```


#### Inside the virtual environment, verify the last version of pip is installed

```
python -m pip install --upgrade pip
```


Install Django

```
pip install -r requirements.txt
```

Make Migrations

```
python manage.py makemigrations
```

Create the tables for the models in the database

```
python manage.py migrate
```


Create a superuser for the database:

```
python manage.py createsuperuser
```


Run the server

```
python manage.py runserver
```


Access locally to the Blog Post at

```
http://127.0.0.1:8000/
```


## Acknowledgments

* This blog was developed following the tutorial of [Django Girls](https://tutorial.djangogirls.org/en/)
