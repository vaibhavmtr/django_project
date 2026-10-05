```
python3 -m venv .venv
source .venv/bin/activate
pip install uv
```
... Now add uv at start of installing anything
```
uv pip install Django 
django-admin startproject commerce_app
cd commerce_app
python manage.py runserver
```