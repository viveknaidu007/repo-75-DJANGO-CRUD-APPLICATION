# repo-75-DJANGO-CRUD-APPLICATION
im creating an mini project using django framework


# for creating environment :
conda create --name django python=3.10

# for activating environemnt :
conda activate djnago

# as we know django has :
1.django has project 
2.as well as application

# now run this:
django-admin startproject project                 #give any name in the porject name as ur wish


# for running the project :
cd project
python manage.py runserver

# now create applicatin server:
cd project
python manage.py startapp app                  #give any name ur wish in the place of app
*after you run this , app folder will create and migrations folder will also create inside app fodler

# install this in extentions:
it will give good sugetions while u r typing
and also python
and pretier

# we need to register/load the app in setting.py
"app"

# add templates names in 'DIRS' : [] in settings.py

# add urls.py in migration app folder

# render the index.html in views.py in app foler

# create path for index.html
#
python manage.py startapp app

# for runnig the code:
python manage.py runserver

#
python manage.py makemigrations

#
python manage.py migrate

# for creating a an admin name to login and see
python manage.py createsuperuser


