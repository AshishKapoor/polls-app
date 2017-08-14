web:python manage.py runserver
web: gunicorn mysite.wsgi:application --log-file -
worker: python worker.py
heroku ps:scale web=1
