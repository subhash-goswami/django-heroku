release: python src/manage.py makemigrations
release: python src/manage.py migrate
web: gunicorn --pythonpath src app.wsgi --log-file -
