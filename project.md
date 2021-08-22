# CS50 Final Project

---

Purpose of software:

* Family web-app, to help keep family tasks and events organized.

Features:

* Calendar to keep track of dates/responsibilities
* Master user (parent) that can access all special features
* User accounts that show a calendar and list of upcoming important things
* Family forum/blog to have messages

Execution:

* By the use of a flask app hosted on heroku


Skills to acquire:

* Learn Flask, especially how to have different users with different access login
* Learn how to host the webapp on site like heroku
* Learn how to use api's especially for the calendar


Outcomes:

* Good: A hosted webapp where users can all log in and see a list
* Better: 
* Best: Get the permissions working etc.

---

#### 22-08-21

I am using the windows terminal, and writing in VIM in Powershell to do the code in Python and also write the html.  

The first thing I'm going to do is create a virtual environment for Flask in which to write the code.  

    python -m venv .venv

Next to activate the environment  

    ./.venv/Scripts/Activate.ps1

I'll install some dependencies for the Flask application to work along with some helpers for the validations and forms:  

    pip install flask, flask-wtf, wtforms, flask-login, flask-sqlalchemy, email-validator, flask-session

I'll creat a .gitignore file and then initialize a git repository:  

    git init
