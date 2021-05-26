release: python manage.py makemigrations
release: python manage.py migrate
web: gunicorn --pythonpath src app.wsgi --log-file -
