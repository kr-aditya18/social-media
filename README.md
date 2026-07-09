# Social Media Platform (Django)

![Project Banner](https://raw.githubusercontent.com/Ayushsav/social-media/main/socialmedia/media/post_images/show.png)

A small social media platform built with Django — register, post updates, follow other users, and see their posts in your feed.

Live: https://social-media-17h9.onrender.com/

## Features

- User registration and authentication
- Profiles with profile pictures and bio
- News feed showing posts from people you follow
- Create and delete posts
- Like posts
- Follow / unfollow users
- Search for users

## Local Setup

```bash
git clone https://github.com/kr-aditya18/social-media.git
cd social-media/socialmedia
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```

Then visit `http://127.0.0.1:8000/`, register an account, and start posting and following other users.

## Live Demo

https://social-media-17h9.onrender.com/
