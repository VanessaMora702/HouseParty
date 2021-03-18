# HouseParty
Tech Stack: Python, Django, JS, and React
Will be using 3rd party API's such as Google and Spotify.

Collaborative Music Playing System
Full Stack project that will allow user's to control the music that is being played 
There will be one host who can create a room.  It wil be the user thats controlling the music where ever they are house party, restaurant etc..
The host user will be able to give out a code to other users and allow them to join the room that will allow them to control the music.
# Project
pip install django djangoframework
<!-- create django project -->
django-admin startproject nameOfApp
django-admin startapp api
<!-- initialize db-- django default db -->
python manage.py makemigrations
python manage.py migrate
<!-- run server -->
python mange.py runserver

# Install Swagger UI
pip install pyyaml uritemplate
pip install django-rest-swagger
# React, Webpack and Babel
<!-- create another django app call frontend  -->
django-admin startapp frontend
<!-- crated src/componets folder static/frontend,css,images folder -->
<!-- npm init -y creates a package.json file for you-->
npm init -y
<!-- transpiles the code into one JS file-->
npm i webpack webpack-cli --save-dev
<!-- babel new js ES6/ES& cod and coverts it into code that is friendly with older browsers -->
npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
<!-- allow async and await -->
npm i @babel/plugin-proposal-class-properties
<!-- install react-->
npm i react react-dom --save-dev
<!-- install materialUI library -->
npm i @material-ui/core
npm i @material-ui/icons
<!-- install reeact router -->
npm i react-router-dom

