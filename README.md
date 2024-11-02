# CRUD Application with MongoDB Atlas

This is a simple CRUD (Create, Read, Update, Delete) application built with Node.js, Express, and MongoDB. The application allows users to fill out a form, view user data, and edit or delete user entries stored in a MongoDB Atlas database.

## Features

- User registration form to submit data (first name, last name, email, password)
- Display of registered users with options to edit or delete entries
- Secure password storage using bcrypt
- Connects to MongoDB Atlas for data persistence

## Technologies Used

- Node.js
- Express.js
- MongoDB (Atlas)
- Mongoose (ORM for MongoDB)
- EJS (Embedded JavaScript templating)
- Body-parser (to handle form submissions)
- Bcrypt (for password hashing)

## Install dependencies:
-Make sure you have Node.js installed, then run:
Run the application:
```bash
npm install
```
## Set up your environment variables:
Create a .env file in the root directory with the following content
```bash
MONGODB_URI=mongodb+srv://<your_username>:<your_password>@cluster0.53nvo.mongodb.net/your_database_name?retryWrites=true&w=majority
PORT=3001
BCRYPT_SALT_ROUNDS=10
```
## Run the application:
```bash
node server.js
```
The application will run at http://localhost:3001.