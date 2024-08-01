# Django-Web-Scraping
Web Scraping with Python's Django

**Setting up Django Project using VS Code:**
- on cmd --> cd C:\Users\akunna1\Desktop\django_project
- set up venv using pip install virtualenv
- python -m venv venv
- venv\scripts\activate
- pip install django
- django-admin startproject project1
- cd project1
- python manage.py startapp app1
- In app1 there's models.py(for backend, where to set up db), view.py(for running db, for setting up requests), tests.py(for running tests)
- python manage.py startapp app1
- add app1 to settings.py
- python manage.py runserver
