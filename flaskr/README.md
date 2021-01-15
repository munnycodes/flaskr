# Flaskr
For this project, ensure that you have `python3`, `pip3` and `virtualenv` library set up.
### Setup
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





### Data Model



### File Structure   
The project directory contains:
## 1. Flaskr/
This is the python package that contains the application code and files. 
## 2. Tests/
This contains all the test modules that ensure the code works as expected.
## 3. venv/
This contains the virtual environment where Flask and other dependencies are installed. 
for more information on virtual environments go to: (https://docs.python.org/3/library/venv.html "Creation of virtual environments")
/home/user/Projects/flask-tutorial
├── flaskr/
│   ├── __init__.py
│   ├── db.py
│   ├── schema.sql
│   ├── auth.py
│   ├── blog.py
│   ├── templates/
│   │   ├── base.html
│   │   ├── auth/
│   │   │   ├── login.html
│   │   │   └── register.html
│   │   └── blog/
│   │       ├── create.html
│   │       ├── index.html
│   │       └── update.html
│   └── static/
│       └── style.css
├── tests/
│   ├── conftest.py
│   ├── data.sql
│   ├── test_factory.py
│   ├── test_db.py
│   ├── test_auth.py
│   └── test_blog.py
├── venv/
├── setup.py
└── MANIFEST.in