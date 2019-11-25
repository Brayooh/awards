# Awards
##### Project-Review is a platform where users can upload  their projects and project detail, the project is to be rated and reviewed by other users. They can also review other people's projects, search for projects and view overall score.



### Requirements
##### These are the requirements you need to get the project running locally on your machine:
  - Text Editor
  - Install python
  - Install and activate virtual
  - Setup Database
  - Install Django
  - Install Postman



### Installation Process
##### Download any text editor of your choice, either Sublime, Visual-Studio-Code or Atom.
##### Install your preferred version of python
  - ```sudo apt-get install python3.6```.
  - ```python --version``` to confirm that python has been installed.
##### Open the command-line and run the following command to open a directory:
  - ```cd your preferred directory``` => ```cd Desktop```
##### Git clone the project on your current directory by:
  - ```git clone https://github.com/IreneMercy/Project-Review.git```.
##### Move to your project directory:
- ```cd Project-Review```.
##### Open the project on your terminal:
  - ```atom . or code .``` , according to the type of your text editor.
##### Install virtual environment using python:
  - ```python3.6 -m venv virtual```, check your project to confirm you have a folder called virtual,
  - then activate it by running ```source virtual/bin/activate```
##### To install the packages in the ```requirements.txt file```,
  - ```pip install -r requirements.txt```  That will install all packages including Django.
##### To open python shell:
  - ```python3.6``` ,
  - ```import django```
  - And lastly ```django.get_version()``` to see and confirm the version of django installed.
  - You can then ```ctrl z``` to get out of the shell,
##### After ensuring you have all the above
  - ```python3 manage.py runserver``` to run the project.
  - Then click the local host link given to open the project on a browser ```http://127.0.0.1:8000/```.


#### For more information read the following django and python documentation:
  - [DjangoDocumentation](https://docs.djangoproject.com/en/1.11/intro/install/)
  - [PythonDocumentation](https://www.python.org/doc/)





### User Stories
##### As a user, I would like to view posted projects and their details.
##### As a user, I would like to post a project to be rated and reviewed.
##### As a user, I would like to rate and  review other users' projects.
##### As a user, I would like to search for projects .
##### As a user, I would like to view projects overall score.
##### As a user, I would like to view my profile page.

### Behavior Driven Development
#### Given that a user has logged  in successfully, then they should be able to see other peoples projects and review them, they can also post their own projects to be reviewed.
#### Given that a user has logged in, then they should be able to search for different projects.
#### Given that a user is logged in, then they should be able to view projects overall score .
#### Given that a user is logged in and updated their profile, then they should be able to  view their profile.



### Technologies Used
##### Python
##### Django
##### PostgreSQL
##### HTML5
##### CSS3
##### Postman



### Licence
[MIT](LICENSE)


### Contact
##### brianndichu.bn@gmail.com
