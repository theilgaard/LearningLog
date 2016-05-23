# LearningLog
Small database backed multi-user application to track notes on different topics learned.

## Goal
The goal of the application was for me to gain familiarity with Django web framework. The project has been built in an MVC structure, and utilizes the SQLite database.

## Usage
Install Python, no further packages are needed as the virtual environments comes with the Django requirements.

Then activate the virtual environment, migrate the DB and start the server.

~~~~
$ source 11_env/bin/activate
$ python manage.py migrate
$ python manage.py runserver
~~~~

Open http://127.0.0.1:8000
