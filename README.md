# Blog

This is a pet project with REST API without frontend.

## Features

- Create users through the admin panel
- User Authorization and Authentication
- Create and edit posts with title and description
- Only the author himself can interact with posts
- Create and add categories to posts

## Prerequisites

Be sure you have the following installed on your development machine:

- Python >= 3.7
- Git
- pip
- venv

## Requirements

- Django==3.1.7
- djangorestframework==3.12.4
- psycopg2==2.9.9
- pytest==8.3.2
- pytest-django==4.8.0
- pytz==2024.1
- sqlparse==0.5.1

## Project Installation

To setup a local development environment:

Create a virtual environment in which to install Python pip packages. With venv:

```
python -m venv myenv
myenv\Scripts\activate     # for Windows
source myenv/bin/activate  # for Linux
```

Or with  virtualenv:

```
virtualenv venv            # create a virtualenv
source venv/bin/activate   # activate the Python virtualenv 
```

Clone GitHub Project,

```
git clone https://github.com/VeronikaPotseichuk/Blog.git
cd Blog
```

Install development dependencies:

```
pip install -r requirements.txt
```

Migrate Database:

```
python manage.py migrate
```

Run the web application locally:

```
python manage.py runserver # 127.0.0.1:8000
```

Create Superuser:

```
python manage.py createsuperuser
```

Run tests:

```
pytest
```
