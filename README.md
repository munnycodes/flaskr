# flaskr
# Flaskr
This is a basic blog application called Flaskr. Users are able to register, log in, create posts and edit or delete their own posts. 

## Table of Contents
* [Setup](#setup)
* [File Structure](#file-structure)
    * [Flaskr](#flaskr)
    * [Tests](#tests)
    * [Venv](#venv)
* [Database](#database)


For this project, ensure that you have `python3`, `pip3` and `virtualenv` library set up.
# Setup
1. Clone this repo onto your local machine.
2. From the root directory, create a virtualenv with the command:
    `python3 -m venv <name of your env>`
3. Activate your virtual env by entering the following command:
    `source <env>/bin/activate`
3. Install requirements:
    `pip install -r requirements.txt`
4. Run the app using the commands:
    `$ export FLASK_APP=flaskr`
    `$ flask run`
5. In your browser enter the following URL:
    `http://127.0.0.1:5000/`







# File Structure   
The file structure is laid out as follows:
## 1. Flaskr/
This is the python package that contains the application code and files. Some of the files that are in this directory are: 


**schema.sql** Contains the sql set up for the database.


**db.py**  Contains the database functions. 


**auth.py** contains the functions and routes for registering, logging in and logging out. 


**static/style.css** the style definitions are saved here. If you want to change the look of the website you can edit this file.


**blog.py** contains blog related functions and routes. The functions that allow you to create, post, update and delete blog posts. 
When creating a blog post, errors are thrown if any of the fields are incomplete. 

## 2. Tests/
The tests directory contains comprehensive tests that ensure the code works as expected.
If you wish to run the tests, enter the following commands into your terminal:
`$ pip install '.[test]'`
`$ pytest`

## 3. venv/
This contains the virtual environment where Flask and other dependencies are installed. 


For more information on virtual environments go to: (https://docs.python.org/3/library/venv.html "Creation of virtual environments")

### Database
The application uses a SQLite database to store users and posts. 



