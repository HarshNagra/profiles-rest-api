# Profiles Rest API using DJANGO

Introductory project to Django Framework to create a RESTful API.

### Development Server
Vagrant and VirtualBox 

### Application Code
1. Python
2. Django
3. Django Rest Framework

### Tools
ModHeader - To modify HTTP headers.

#### Vagrant

`vagrant init ubuntu/bionic64` creating a server

Copy the code from Vagrantfile on this repository to your local repository.

`vagrant up` to create the development server.

Isolated machine is ready.

`vagrant ssh` to run the development server.

On the devlopment server `cd /vagrant`

Creating python Virtual Environment `python -m venv ~/env` (Created in home directory '~')

`source ~/env/bin/activate` to start the virtual environment

`deactivate` to deactivate the virtual environment

## In the python virtual environment:

`cd /vagrant`

`pip install -r requirements.txt`

`django-admin.py startproject profiles_project .` To create a django project.

`python manage.py startapp profiles_api` to create Django App.

`python manage.py server 0.0.0.0:8000` To run the Django Development Web Server.


