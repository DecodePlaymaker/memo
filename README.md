# Memo

Module 11 Challenge: Note taker

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Description
This application was designed to give users a place to store notes to help them organize their thoughts and to keep track of tasks they need to complete. It is powered by Express and JavaScript and implements an imitation database using a json file (db.json) to save and retrieve data. I was responsible for connecting the backend and frontend of this application through the use of GET, POST, and DELETE requests within Express which allows users to save, retrieve, post new data, and delete data from the application by use of the front end user interface (UI). I utilized an application called Insomnia to test GET, POST, and DELETE routes.

## Live URL of Deployed Application
Deployed on Heroku

https://safe-anchorage-35123-b61c5df82ac5.herokuapp.com/notes

## Screenshot
![Screenshot2](/images/intro.png)
![Screenshot1](/images/Note.png)

## Installation Process
1. Clone the repo:
   git clone git@github.com:DecodePlaymaker/memo.git

2. Open in VS Code. If you do not have VS code you must install it.

3. Using the terminal, install node.js v16. If you have homebrew, the command should look like the following (brew install node@16)

4. Once node.js v16 is installed, in the terminal, utilize the command npm init -y to initialize and create a package.json where project files will be stored.

5. Next, use the terminal to run the command npm i to install the dependencies associated with this application (developers may need to install express and uniqid directly from the command line, to do so the command for express will be npm i express to install the latests version of Express framework globally so that it can be used within the node terminal, and npm i uniqid to install the latest version of uniqid).

6. To run the server, within the terminal, type the command npm start or node server.js.

7. Once the server is running, users can then access the front end of the application within the browser to observe full functionality of the site.
