# Prepare the environment to run: #
* brew install tree
* pip install boto boto3
* easy_install pip
* pip install django
* pip install virtualenv
* pip install pip --upgrade
* pip install djangorestframework==3.3
* pip install django==1.9
* pip install django-cors-headers==1.1
* virtualenv venv

# Run: #
* source venv/bin/activate
* cd src/
<<<<<<< HEAD
* python manage.py runserver

# Run Tests: #
* python manage.py test
=======
* python manage.py migrate
* python manage.py runserver
>>>>>>> a325194af93cb89682db4274e641be67fcdf9037
