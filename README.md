# AirBnB Clone Phase 3

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General

    What REST means
    What API means
    What CORS means
    What is an API
    What is a REST API
    What are other type of APIs
    Which is the HTTP method to retrieve resource(s)
    Which is the HTTP method to create a resource
    Which is the HTTP method to update resource
    Which is the HTTP method to delete resource
    How to request REST API

## Requirements
Python Scripts

    Allowed editors: vi, vim, emacs
    All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.8.5)
    All your files should end with a new line
    The first line of all your files should be exactly #!/usr/bin/python3
    A README.md file, at the root of the folder of the project, is mandatory
    Your code should use the pycodestyle (version 2.7.*)
    All your files must be executable
    The length of your files will be tested using wc
    All your modules should have documentation (python3 -c 'print(__import__("my_module").__doc__)')
    All your classes should have documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
    All your functions (inside and outside a class) should have documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
    A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

## Python Unit Tests

    Allowed editors: vi, vim, emacs
    All your files should end with a new line
    All your test files should be inside a folder tests
    You have to use the unittest module
    All your test files should be python files (extension: .py)
    All your test files and folders should start by test_
    Your file organization in the tests folder should be the same as your project: ex: for models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
    All your tests should be executed by using this command: python3 -m unittest discover tests
    You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
    We strongly encourage you to work together on test cases, so that you don’t miss any edge cases

## Description

Project attempts to clone the the AirBnB application and website, including the database, storage, RESTful API, Web Framework, and Front End. Currently the application is designed to run with 2 storage engine models:

 *  File Storage Engine:
        /models/engine/file_storage.py

* Database Storage Engine:
 /models/engine/db_storage.py

   To Setup the DataBase for testing and development, there are 2 setup scripts that setup a database with certain privileges: setup_mysql_test.sql & setup_mysql_test.sql (for more on setup, see below).

   The Database uses Environmental Variables for tests.

## Enviroment
* OS: Ubuntu 14.04 LTS
* language: Python 3.4.3
* web server: nginx/1.4.6
* application server: Flask 0.12.2, Jinja2 2.9.6
* web server gateway: gunicorn (version 19.7.1)
* database: mysql Ver 14.14 Distrib 5.7.18


## Authors:

Omar Velez natzuac@yahoo.com
Jose Nieves 6845@holbertonstudents.com
