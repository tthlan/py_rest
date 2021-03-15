# py_rest
django rest framework tutorial

3) install httpie using pip:

pip install httpie

ex: get a list of all of the snippets:
http http://127.0.0.1:8000/snippets/


2) create an initial migration for our snippet model, and sync the database for the first time.

python manage.py makemigrations snippets
python manage.py migrate


1) install our package requirements.

pip install django
pip install djangorestframework
pip install pygments