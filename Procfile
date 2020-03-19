web: gunicorn django_projectt.wsgi.applicatio --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate
