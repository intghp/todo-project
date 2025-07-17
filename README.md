# Initial Settings
- python -m venv venv
- venv/Scripts/activate
- pip install -r requirements.txt
- django-admin startproject core .
- python manage.py startapp todo
- python manage.py migrate
- python manage.py runserver

# Setting Up Backend
- python manage.py makemigrations todo
- python manage.py migrate todo
- python manage.py createsuperuser
- python manage.py runserver

# Setting Up Frontend
- npx create-react-app frontend
- cd frontend / npm start
