# A Full-Stack Django Web Application

This is a full-stack Django Web Application that uses a Postgres database and is connected to AWS. Currently it is deployed to Heroku and can be viewed from this [link](https://django-devsearch-webapp-5bd124229307.herokuapp.com/). Feel free to create an account, add a project, or play around with any of the features. Everything is secure.

This is a typical Django application with function-based views and many templates. There are two apps: the projects app and the users app. This website serves as a website where developers can create an account, share their projects with other developers, and message each other. There are many database models (from Review's to Profile's to Project's) to ensure that the desired functionality on the frontend works.

Additionally, the project includes an API for anyone who would like to access and interact with certain objects in the database. Another project on my GitHub profile titled "frontend" makes API calls to this project to populate a separate app with data from this project. Additionally, users can upvote or downvote projects using the API. The code first verifies users and then adds a token to their cookies so that subsequent API calls are authorized.

Feel free to take a look at the [website](https://django-devsearch-webapp-5bd124229307.herokuapp.com/) yourself. I am sure viewing the code in a browser will be more interesting. Lastly, this project is mostly based on a series of Django tutorials made by a [Django programmer on YouTube](https://www.youtube.com/@DennisIvy). Feel free to check his work as I owe learning the Django framework and creating a working application to him.

## Technologies Used
Django, HTML, CSS, JavaScript, SQLite (in development), Postgres AWS S3 and RDS (in production)

## List of all Python libraries used
* asgiref                       3.7.2
* boto3                         1.28.25
* botocore                      1.31.25
* Django                        4.2.2
* django-cors-headers           4.2.0
* django-storages               1.13.2
* djangorestframework           3.14.0
* djangorestframework-simplejwt 5.2.2
* gunicorn                      21.2.0
* jmespath                      1.0.1
* packaging                     23.1
* Pillow                        9.5.0
* pip                           23.2.1
* psycopg2                      2.9.7
* PyJWT                         2.8.0
* python-dateutil               2.8.2
* python-decouple               3.8
* pytz                          2023.3
* s3transfer                    0.6.1
* setuptools                    65.5.0
* six                           1.16.0
* sqlparse                      0.4.4
* urllib3                       1.26.16
* whitenoise                    6.5.0