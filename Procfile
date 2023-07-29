release: python manage.py makemigrations && python manage.py migrate
web: gunicorn tech_things.wsgi:application