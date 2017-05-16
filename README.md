# The Flask Mega Tutorial
Tutorial to start learning Flask web framework.

[by Miguel Grinberg]()


## Installation
- cd microblog

    ```
    python3 -m venv flask
    flask/bin/pip install flask
    flask/bin/pip install flask-login
    flask/bin/pip install flask-openid
    flask/bin/pip install flask-mail
    flask/bin/pip install flask-sqlalchemy
    flask/bin/pip install sqlalchemy-migrate
    flask/bin/pip install flask-whooshalchemy
    flask/bin/pip install flask-wtf
    flask/bin/pip install flask-babel
    flask/bin/pip install guess_language
    flask/bin/pip install flipflop
    flask/bin/pip install coverage
    ```


## Usage
- To start the app:

    ```
    chmod a+x run.py
    ```

- To execute the script:

    ```
    ./run.py
    ```

- URL to open on web browser
    
    ```
    http://localhost:5000/index
    ```

---

## Table of Contents

- [Microblog](https://github.com/PukkaPad/flask-mega-tutorial/tree/master/microblog)
    - Flask 
    - [app](#app) 
        - static
        - [templates](#templates)
    - [tmp](#tmp)

## Flask
I have a complete `python3` environment inside this folder. I also have the Flask framework and extensions that will be used for the application.

## app
Where the application package is.

### static
For storing static files (images, javascripts)

### templates
For templates