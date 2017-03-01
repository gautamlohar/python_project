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

# Python Models nd createing a simple Blog Modules
- TO start first create the app blog with the command "django-admin.py startapp blog", if all goes according to plan, you’ll now have a directory structure like below. If yours isn’t, then move the blog directory so it’s sitting inside the project root.
- Edit the \first_project\blog\settings.py add 'blog' on INSTALLED_APP
- Edit the \first_project\blog\models.py and add the "Post" model and other lines of code as mentioned in the file stored here
- Edit the \first_project\blog\admin.py and Register Post models here
- On command prompt run command "python manage.py makemigrations"
- Then run "python manage.py migrate"
- Now you can check blog and everything working fine on the URL http://127.0.0.1:8000/admin/blog/