# Django project skeleton

django-project-skeleton is my skeleton for Django projects. It provides a directory structure for Django projects during development and deployment.

This structure is based on research and own experience of developing Django apps.

# Requirements
python 3.5 or higher;

# Installation

## Create an environment
Create a project folder and a venv folder within:

``` bash
$ python3 -m venv venv
```

# Install dependencies
Now, you will need to set up virtual environment that will keep the application and its dependencies isolated from the main system.

Next run the following command with the name of your temporary virtual environment.

``` bash
$ source venv/bin/activate
```

Now, run following command to install Flask dependency inside it:

``` bash
$ pip install -r requirements/dev.txt
```

# Usage
Run this command to run the built-in web server and access the application in your browser at http://localhost:8000:

``` bash
$ python3 manage.py runserver
```
