# This is Practice 1, it starts from install and create a project

## Installation of Django

1. Firstly, use the command line to install Django. Here, I used an environment named _dj_ for this practice. 
    ```bash
    # Install Django
    (dj) pineapple@pineapple % pip install django
    ```

## Create a Django Project

2. Use the command line:
    ```bash
    django-admin startproject myproject
    ```
    This initializes the first project named _myproject_ under the current directory.

## Applications are Sub-modules of a Project

3. Use the command:
    ```bash
    python manage.py startapp ads
    ```
    This creates an app called _ads_ under the _ads_ directory.

## Run Server

4.  ```bash
    python manage.py runserver
    ```
    This runs the server for development, and visit the URL `http://127.0.0.1:8000/`.

