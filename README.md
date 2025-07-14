python -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
django-admin startproject core .
python manage.py startapp todo
python manage.py migrate
python manage.py runserver