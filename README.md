# Project

Django-blog-project

Install the following dependencies for this to work


Note: 

Make sure you have python 3 and not 2!!

Make sure you activate the virtual environment provided here(iso_venv) or install the following versions in your virtual                              environment

    pip install django==2.0.6

    sudo apt-get install python3.6-dev

    pip install channels

    pip install channels_redis
    
Before running , make sure you run the redis server first To run the chat,first run : sudo docker run -p 6379:6379 -d                                 redis:2.8

After this to run, type python3 manage.py runserver 

The home page can be reached by clicking on the page title 'Blogger:Publish your passions,your way'




Features
          
    Add Blogs, Edit Blogs ,Remove Blogs 

    Each Blog has Comments

    Chat Rooms using channels

    Authentication using Login and Logout

    Sign Up for new users

    Registration for new Users and login in for registered users is possible through the home page. 
