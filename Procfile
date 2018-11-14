web: gunicorn config.wsgi:application
worker: celery worker --app=cookie_site.taskapp --loglevel=info
