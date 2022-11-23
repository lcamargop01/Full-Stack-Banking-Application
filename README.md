# Fullstack Banking Application 

## The BadBank

This Fullstack banking application emulates how a withdraw and deposit works on a bank. It has `login` and `create account` tabs that you need to sign up/in with first to authenticate the users access before you can use the `withdraw` and `deposit` features, the credentials for registers users are placed on the `All Data` tab. 

This project was bootstrapped with [Create React App].  

<img width="1195" alt="Screen Shot 2022-07-05 at 6 48 43 PM" src="https://user-images.githubusercontent.com/89609365/177429811-a918a3b5-d149-43b5-a765-46cb0f5d9a2a.png">

https://seman-michelle-badbank2.herokuapp.com/#/

## Installation guide

accessing the code

* Clone the git repository

Install dependencies for server & client

* npm install

Run client & server with concurrently

* npm run dev

Server runs on http://localhost:5000 and client on http://localhost:3000

** Be sure to add your custom MONGO_URI to the .env file 

## Tech Stack - MERN
### Client Side
* HTML
* CSS
* JavaScript
* React js
* Formik
* Bootstrap (card, navbar)
### Server Side
* MongoDB
* Mongoose
* Express
* Node.js

## Features
* create account
* login
* deposit
* withdraw
* retrieve all data

## To-Do
- [ ] add log-out capability
- [ ] add OAuth2 authentication
- [ ] make all data only accessible once the user is logged in

## License
[MIT](https://choosealicense.com/licenses/mit/)
