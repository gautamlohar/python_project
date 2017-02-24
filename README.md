# python_project 1
> Install Python 
- Use git bash or command prompt
- Download the python.exe   Python 27
- Download pip and install
- Download and install sqllite ( as Database )
- Set environment variable if not installed globally
- Go to the project directory and install django. e:\project\project_name> pip install django.
- then run command: django-admin startproject
-	Gautam Lohar@Gautam MINGW64 /e/xampp/htdocs/python_project (master)
	django-admin startproject first_project (when you will run this command, you will get manage.py file, which the core)

-	Gautam Lohar@Gautam MINGW64 /e/xampp/htdocs/python_project (master)
	cd first_project/
-	Gautam Lohar@Gautam MINGW64 /e/xampp/htdocs/python_project/first_project (master)
	python manage.py (To check all available python functions)
-	python manage.py createsuperuser (It will ask for username and password creation)
	If you face with error "Superuser creation skipped due to not running in a TTY. You can run `manage.py createsuperuser` in your project to create one manually" Then do run  this  ( alias python='winpty python' )
-	And Again run "python manage.py createsuperuser (It will ask for username and password creation)
-	python manage.py migrate
-	python manage.py runserver
-	This will be the URL of your django framework http://127.0.0.1:8000/
-	This will be the ADMIN URL of your django framework http://127.0.0.1:8000/admin

