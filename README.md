# 🐍 Django-Blog

````bash
echo "# Django-Blog" >> README.md

git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/Joaosilgo/Django-Blog.git

git push -u origin master

````

````bash
 Admin
 Username JoaoGomes

 python

 python manage.py shell
 from django.contrib.auth.models import User
 User.objects.get(username="JoaoGomes", is_superuser=True).delete()

bash

ls

python manage.py createsuperuser

python manager.py migrate
 ````

 ````bash
 asgiref==3.2.10
astroid==2.4.2
autopep8==1.5.4
beautifulsoup4==4.9.1
bs4==0.0.1
certifi==2020.6.20
chardet==3.0.4
colorama==0.4.3
dj-database-url==0.5.0
Django==3.0.8
django-crispy-forms==1.9.2
django-heroku==0.3.1
gunicorn==20.0.4
idna==2.10
isort==4.3.21
lazy-object-proxy==1.4.3
mccabe==0.6.1
Pillow==7.2.0
psycopg2==2.8.6
pycodestyle==2.6.0
pylint==2.5.3
pylint-django==2.3.0
pylint-plugin-utils==0.6
pytz==2020.1
requests==2.24.0
six==1.15.0
soupsieve==2.0.1
sqlparse==0.3.1
toml==0.10.1
urllib3==1.25.10
whitenoise==5.2.0
wrapt==1.12.1

 ````
