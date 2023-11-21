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
![Screenshot 2023-11-21 140448](https://github.com/Kamal-Raj-A/ODD2023-WT-Ex-04-Django-Models/assets/145742556/64c18bbe-3ea9-44d4-b8d3-00c147ab849b)


add the models in the admin interface using the code admin.py
![image](https://github.com/Kamal-Raj-A/ODD2023-WT-Ex-04-Django-Models/assets/145742556/895488d3-166c-4bec-a407-3e3879add922)


write the function based view to render the data from the models to the template in views.py
![image](https://github.com/Kamal-Raj-A/ODD2023-WT-Ex-04-Django-Models/assets/145742556/7dff2295-02c4-4875-8695-9efb60d2067d)


set up the url path for the templates using urls.py
![image](https://github.com/Kamal-Raj-A/ODD2023-WT-Ex-04-Django-Models/assets/145742556/6af75c8d-456d-486a-94c2-66fe8544c00f)


in settings.py file add the appcreated

step 3: Now do the migrations process to initiate and save the models
python manage.py makemigrations python manage.py migrate create a template as user_profile.html


step4: Run the program using the following command
python manage.py runserver 8000 in the admin page you can view the models created and in the user_profile template page you can see the profile page of the user.

# output:
![image](https://github.com/Kamal-Raj-A/ODD2023-WT-Ex-04-Django-Models/assets/145742556/26df06ae-c524-4389-b510-879e72761aac)


![Screenshot 2023-11-21 034359](https://github.com/Kamal-Raj-A/ODD2023-WT-Ex-04-Django-Models/assets/145742556/f1a573a7-14fd-45b9-b83f-187e646b9aaf)



# Result:
Django model was created successfully
