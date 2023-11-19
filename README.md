
![Screenshot 2023-11-18 at 10 04 03 PM](https://github.com/Yeranosyan/my-course-repo/assets/120154377/3c36b788-d653-43b0-90b8-2373d98d7d59)


**General Notes**

An `onlinecourse` app has already been provided in this repo upon which you will be adding a new assesement feature.

- If you want to develop the final project on Theia hosted by [IBM Developer Skills Network](https://labs.cognitiveclass.ai/), you will need to create the same project structure on Theia workspace and save it everytime you close the browser
- Or you could develop the final project locally by setting up your own Python runtime and IDE
- Hints for the final project are left on source code files
- You may choose any cloud platform for deployment (default is IBM Cloud Foundry)
- Depends on your deployment, you may choose any SQL database Django supported such as SQLite3, PostgreSQL, and MySQL (default is SQLite3)

**ER Diagram**
For your reference, we have prepared the ER diagram design for the new assesement feature.

![Onlinecourse ER Diagram](https://github.com/ibm-developer-skills-network/final-cloud-app-with-database/blob/master/static/media/course_images/onlinecourse_app_er.png)

# Objectives
## Understand the requirements of the new course assessment feature
## Create question, choice, and submission models
## Create a new course object with exam related models using the admin site
## Update the course details template to show questions and choices
## Create a new exam result template to show the result of the submission
## Create a new exam result submission view
## Create a new view to display and evaluate exam result
![01-models](https://github.com/Yeranosyan/my-course-repo/assets/120154377/7dc1a761-214c-4bfc-977d-9f0bbf4bff9c)
![02-admin-file](https://github.com/Yeranosyan/my-course-repo/assets/120154377/55d756b4-18cc-4178-b558-f204d5e648d0)
![03-admin-site](https://github.com/Yeranosyan/my-course-repo/assets/120154377/583cbd0a-73b5-413a-8e7e-33af68eb5c8f)
![04-course-details](https://github.com/Yeranosyan/my-course-repo/assets/120154377/93ecc812-ec61-43d4-84c4-c74b10278ca7)
![05-views](https://github.com/Yeranosyan/my-course-repo/assets/120154377/bd68e54e-8f51-49e4-9b3c-11657ba01710)
![06-urls](https://github.com/Yeranosyan/my-course-repo/assets/120154377/1309d3e0-5c40-49ec-97e0-cf57a8185869)
![07-final](https://github.com/Yeranosyan/my-course-repo/assets/120154377/0300cde2-2428-41ea-a0f8-09e3f8e6b3d0)

- pip install --upgrade distro-info
- pip3 install --upgrade pip==23.2.1
- pip install virtualenv
- virtualenv djangoenv
- source djangoenv/bin/activate
- pip install -U -r requirements.txt
- python3 manage.py makemigrations
- python3 manage.py migrate
- python3 manage.py runserver

- python3 manage.py createsuperuser
- Username: admin
- Email address: leave blank by pressing enter
- Password: Your choice, or use p@ssword123
