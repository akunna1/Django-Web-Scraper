# Django-Web-Scraping

A web application built with **Python's Django** framework that scrapes product listings from **Jumia Nigeria** 🛍️, one of the country’s largest online retailers.

---

## Project Overview

This Django-based scraper is designed to navigate and extract product data—such as names, prices, and descriptions—from **Jumia Nigeria’s** website, making it easy to analyze or reuse the data within a structured web app.

---

## ⚙️ Setup Instructions

Follow these steps to get the project running locally using **VS Code**:

```bash
# Navigate to your desired directory
cd C:\Users\akunna1\Desktop\django_project

# Set up a virtual environment
pip install virtualenv
python -m venv venv
venv\Scripts\activate

# Install Django
pip install django

# Start Django project
django-admin startproject project1
cd project1

# Create a Django app
python manage.py startapp app1

# Add 'app1' to INSTALLED_APPS in project1/settings.py

# Run the server
python manage.py runserver
```

---

## Django File Structure Notes

* `models.py`: Defines database schema
* `views.py`: Handles logic and web scraping requests
* `tests.py`: For writing unit tests
* `urls.py`: (Add if not present) Connects views to URLs

---

## Features

* Scrapes product names, prices, and links from **Jumia Nigeria**
* Display scraped results in a clean web interface
* Built with scalable Django architecture
