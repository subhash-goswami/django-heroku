release: python manage.py makemigrations
release: python manage.py migrate
web: gunicorn src.app.wsgi --log-file -
