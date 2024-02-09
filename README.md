# Django Portfolio Website

Hello, friend!

This project is aimed at developing a small website using Django, which will serve as my portfolio.

## Static Pages

1. **/start_page/**
    - The main portfolio page containing information about my projects and skills.
    - Accessible to all users through the link [http://127.0.0.1:8000/start_page/](http://127.0.0.1:8000/start_page/).

2. **/info/**
    - Admin page assumed to host a chat for work-related communication.
    - Accessible only to authenticated users (administrators).
    - Link: [http://127.0.0.1:8000/info/](http://127.0.0.1:8000/info/).

3. **/location/**
    - Static page with information about the IP addresses of users who visited the site.
    - Link: [http://127.0.0.1:8000/location/](http://127.0.0.1:8000/location/)

## Running the Project

1. Activate the virtual environment and install the necessary packages, including Django.
2. Create a superuser for the site.
3. Start the server.

```bash
# Example commands to run
python3 -m venv venv
source venv/bin/activate
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py createsuperuser
python3 manage.py runserver
```

## Contacts

Author: N.A. Popov <br>
Email: popovn2268@gmail.com

Enjoy your browsing!
