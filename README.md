# restaurant-menu

## Introduction
This is a python module that queries a database for items on restaurant menus and then dynamically generates complete menus in the form of web pages and API endpoints. This module uses Flask framework to develop the application. Users can edit or delete items they've created. Adding, deleteing and editing items require oauth2 authorization.

## Instructions
* go to https://console.developers.google.com/project and login with Google.
* Create a new project
* Name the project
* Select "API's and Auth-> Credentials-> Create a new OAuth client ID" from the project menu
* Select Web Application
* On the consent screen, type in a product name and save.
* In Authorized javascript origins add: http://0.0.0.0:8080 http://localhost:8080
* Click create client ID
* Click download JSON and save it into the root director of this project.
* Rename the JSON file "client_secret.json"

## Steps to run
* Enter into the project folder in command line.
* Type python database_setup.py to initialize the database.
* Type python lotsofmenus.py to populate the database.
* Type python project.py to run the Flask web server. 
* Visit http://localhost:5000 to run.
