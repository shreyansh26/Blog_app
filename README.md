Blog
====

This is a blog webpage with options for the user to post articles and comment on them.
The blog also provides user authentication for users to SignIn, SignUp, and even reset their password if forgotten. Although currently, the confirmation mail is not sent to the user because I do not have any SMTP server set up yet. Howevwe, if run locally, the sample mail can be seeen in the logs. 

------

### Dependecies
* Python 3.5
* Django 1.10

### Installation
1. Install Python 3.5. See [this](https://www.python.org/downloads/ "Python 3.5") for details.
2. Install Django 1.10 using `pip`:
`pip install django==1.10`

### Usage
1. Create a superuser (admin) for handling the web app. `cd` to root of the project and enter in terminal:
```
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```
2. Enter your username, email and password.

3. Enter following in terminal to run server on localhost:
`python manage.py runserver`

4. Visit [http://localhost:8000] to view the app. Login to admin area [http://localhost:8000/admin] to create, manage, edit and delete users, posts and comments. 

------
The Blog has already been deployed at - [Shreyansh's Blog](https://shreyansh26blog.herokuapp.com/ "Blog") 
