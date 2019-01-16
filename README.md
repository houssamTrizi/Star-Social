# Star Social Web app

This is a simple social web application that allows users to create groups and posts topics and make comments on these topics.

## Technologies

- Backend: Python/Django, SQLite 3.
- FrontEnd: html, JavaScript, CSS, Bootstrap.

## Building

Clone the project and install the conda env:

```bash
git clone https://github.com/houssamTrizi/Star-Social.git
conda create -n star_social_env python=3.6

source activate star_social_env
pip install -r requirements.txt
```
Run the app locally:

```bash
python manage.py runserver
```
Then head over to https://localhost:8000/ 

OR deploy to Heroku:

an intance of this app is already built and running with heroku on: https://star-social-2.herokuapp.com/

to deploy a new instance:

```bash
heroku create star-social-2 # be sure this app name is not taken

git push heroku master

heroku run python manage.py migrate

```


## Usage Description

The app allows users to create groups and make posts and comments inside those groups.

Any user can view the groups, posts and comments.

A User can sign up using his email address and password to be able to create a group, make posts or comment on a post.