web: gunicorn config.wsgi:application
worker: celery worker --app=rabbfinance.taskapp --loglevel=info
