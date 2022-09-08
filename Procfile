web: gunicorn todo-2326-app.wsgi:application --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate