# django-social-media
To run this code, follow this step:
1. Make sure you already install django, form crispy, and form crispy bootstrap
2. Before you run the server, do this command first
  - python manage.py makemigrations
  - python manage.py migrate
3. Then make a group called 'mod' on django-admin (you need to create superuser first. Ex: python manage.py createsuperuser. then login to django-admin)
4. In this group, add the permissons 'main | post | add, change, delete, view'
5. You can add some users that already registered to this group 
6. Then run the server (python manage.py runserver)
