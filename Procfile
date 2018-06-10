web: gunicorn config.wsgi:application
worker: celery worker --app=django_broadcast.taskapp --loglevel=info
