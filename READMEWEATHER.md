### Add a Backend to your Weather App

### Introduction

You already have a front-end weather app, and let's add some backend to make it more robust. 
Little fun fact: you build this in week 7! Do you remember week 7?  

# Overview

Hopefully, you already have an app that looks similar to this requirement:
![Screenshoot](https://github.com/Yosolita1978/screenshoots/blob/main/week11/Screen%20Shot%202021-08-20%20at%209.00.38%20AM.png?raw=true)

And hopefully, your project folder distribution looks like this:
* Techtonica Assigments
  - Main Folder Weather App
        - Public
        - Src
        - Readme
        - gitignore
        - package.json
        
Inside your Main Folder Weather App create a new express project (it means to create a new folder for your backend)

### Backend: 
You need to use Postgress and Express to connect your DB. 
Your DB should have a table "users" with at least this columns:
* Users ID
* Favorite City

### Front-End. 
Make sure that when the user searches for a city, that value goes to two places:
* Your API call (this should be already working)
* Your db as the favorite city for the user

#### Features:

 * A list with the five days forecasts (already working)
 * A db that store the favorite city of the user 

#### Extra Features:
* A form so the user can let you their name and email 
  - Your form store those values in the DB, so in this extra feature, your db will have two additional rows: user name  and user email
  - Show a user-visible error message to indicate what's wrong and how the user can fix it
