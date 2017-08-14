web:python manage.py runserver
web: gunicorn mysite.wsgi:polls --log-file -
worker: python worker.py
heroku ps:scale web=1
