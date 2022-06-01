# LAB - Class 28

## Project: Snacks Crud

### Author: Christopher Yamas

### Project Description

A Django project that allows Creating, Reading, Updating and Deleting of Snack items.

### Setup

With this repo on your and Python3 on your local machine, while in root directory run terminal command `pip3 install -r requirements.txt`.

To view the Home page, simply run `python manage.py runserver` and go to the path specified in terminal following the words `Starting development server at`

To view each snack's details page, click on the hyperlinked name of the snack on the Snack List page.

To create a "superuser" account that can access the admin features of the Django project and app, run `python3 manage.py createsuperuser` in the terminal and follow the prompts of for username, email address, and a *strong* password.

### Tests

Tests are contained in the `snacks/tests.py` file.

They can be run in the terminal with command `python manage.py test`.
