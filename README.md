﻿# JavaScript Server - Course assessment 1
# Project name
Harley_Seierstad_Aug22_JSS
# Author 
Harley Seierstad

## Simple overview of use/purpose.
This is a web application created with NodeJS using express with EJS-framework.
Purpose of this program is to be able to show the 100 most popular memes and show specific details about any of the given memes, but only if the user is logged in.

### An in-depth paragraph about your project and overview of use.

This web application have three pages. the first page is the /memes, which is a page that have a table thats being filled by an API call with the top 100 most popular memes. In the table have a search function that can search for any meme thats in the table, it will update itself depending on input in real time. and its not case sensitive. in the table rows you can see the meme name and meme image, and if the user is logged in there will also be a "view Details" button. 
which will take you to the second page that will show you details about whatever meme you clicked on. this page will show extra details about the meme, such as a full size image, meme name, url, ID and the dimensions of the image. 
The third page is the login page where a user can log in and out, and depending on if the user is logged in or not, an extra button will appear on memes overview page aswell as showing the username in the top right corner of the navbar ( will say guest, if not logged in).


### Login information
Login information can be found in data/users.json, Here you can add more logins or delete users if you want. If you want to use another meme api you can change this in data/env.json

### Dependencies
bootstrap 5.2.3 or later
jquery 3.6.3 or later
axios 1.2.2 or later
body-parser 1.20.1 or later
bootstrap 5.2.3 or later
bootstrap-icons 1.10.3 or later
connect-ensure-login 0.1.1 or later
cookie-parser 1.4.4 or later
debug 2.6.9 or later
ejs 3.1.8 or later
express 4.18.2 or later
express-session 1.17.3 or later
express-session-json 0.0.8 or later
http-errors 1.6.3 or later
jquery 3.6.3 or later
local-storage 2.0.0 or later
morgan 1.9.1 or later
passport 0.6.0 or later
passport-local 1.0.0 or later

### Installing
in the terminal "npm install" and it will install all the dependencies
