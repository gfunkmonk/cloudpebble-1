web: newrelic-admin run-program gunicorn -c gunicorn.py cloudpebble.wsgi
#celery: newrelic-admin run-program python manage.py celeryd -E -l info
celery: newrelic-admin run-program celery worker -A cloudpebble -E -l info
