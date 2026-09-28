# Auth API

This project is a basic authentication API built with Node.js and Express.

## What It Does

* Allows users to register
* Hashes passwords using bcrypt
* Allows users to log in
* Checks email and password
* Creates a JWT token after a successful login
* Stores user information in MongoDB

## Technologies Used

* Node.js
* Express
* MongoDB
* Mongoose
* bcrypt
* JSON Web Tokens (JWT)
* dotenv

## How to Run

```bash
npm install
node server.js
```

The server runs on port 3003.

## API Routes

* `POST /api/users/register` — Register a new user
* `POST /api/users/login` — Log in a user
