# Ex-04-Django-Models
# Name:Kamalraj
# Ref no.:23012941
# Department: cse
# Aim:
To create django model
# Design Procedure
Django models
step 1: Create django project and app using the following commands django-admin startproject
mymodels python manage.py startapp myApp

step 2: create a user_profile models in model.py
![Alt text](<Screenshot 2023-11-21 035639.png>)

add the models in the admin interface using the code admin.py
![Alt text](<Screenshot 2023-11-21 035924.png>)

write the function based view to render the data from the models to the template in views.py
![Alt text](<Screenshot 2023-11-21 040150.png>)

set up the url path for the templates using urls.py
![Alt text](image.png)

in settings.py file add the appcreated

step 3: Now do the migrations process to initiate and save the models
python manage.py makemigrations python manage.py migrate create a template as user_profile.html
![Alt text](image-1.png)

step4: Run the program using the following command
python manage.py runserver 8000 in the admin page you can view the models created and in the user_profile template page you can see the profile page of the user.

# output:
![Alt text](image-2.png)

![Alt text](image-3.png)


# Result:
Django model was created successfully
