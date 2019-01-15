# Star Social Web app

This is a simple social web application that allows users to create groups and posts topics and make comments on these topics.

## Technologies

- Backend: Python/Django, SQLite 3.
- FrontEnd: html, JavaScript, CSS, Bootstrap.

## Building

Run these commands to run the web app in a conda env:

```bash
git clone https://github.com/houssamTrizi/Star-Social.git
conda create -n star_social_env python=3.6

pip install -r requirements.txt
python manage.py runserver
```

Then head over to https://localhost:8000/ 


## Usage Description

The app allows users to create groups and make posts and comments inside those groups.

Any user can view the groups, posts and comments.

A User can sign up using his email address and password to be able to create a group, make posts or comment on a post.