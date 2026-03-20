# Deployment Guide

## PythonAnywhere Deployment

1. Create a free account at pythonanywhere.com
2. Upload the project files
3. Set up a virtual environment
4. Configure the WSGI file
5. Reload the web app

## Local Development
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py seed_data
python manage.py runserver
```