# Node-commerce

A full-stack e-commerce backend API built with Node.js, Express, and PostgreSQL.

## Project Overview

Node-commerce is a personal portfolio project designed to demonstrate backend development skills, including RESTful API design, database management, authentication, and secure user session handling.

The project simulates the core functionality of an e-commerce platform by providing endpoints for managing products, users, and orders.

## Technologies Used

* Node.js
* Express.js
* PostgreSQL
* JWT Authentication (In Progress)
* Git & GitHub

## Current Features

### Product Management

* Create products
* Retrieve product listings
* Retrieve individual products
* Update product information
* Delete products

### User Management

* User registration
* User login
* User profile management

### Order Management

* Create orders
* View orders
* Manage order data

## Database Design

The application uses PostgreSQL as the primary database.

Planned database tables include:

* Users
* Products
* Orders
* Order Items

Relationships are designed using foreign keys to maintain data integrity.

## Authentication

JWT (JSON Web Token) authentication is currently being implemented.

Planned features include:

* Secure user registration
* Password hashing
* User login authentication
* Protected routes
* Token validation

## API Endpoints

Example endpoints:

### Products

GET /api/products

GET /api/products/:id

POST /api/products

PUT /api/products/:id

DELETE /api/products/:id

### Users

POST /api/users/register

POST /api/users/login

GET /api/users/profile

### Orders

GET /api/orders

POST /api/orders

GET /api/orders/:id

## Installation

Clone the repository:

git clone https://github.com/htinz/node-commerce.git

Navigate to the project directory:

cd node-commerce

Install dependencies:

npm install

Create a .env file and configure your environment variables.

Start the development server:

npm run dev

## Future Improvements

* Complete JWT authentication
* Role-based authorisation (Admin/User)
* Product categories
* Shopping cart functionality
* Payment gateway integration
* API testing with Jest
* Deployment to a cloud platform

## Learning Objectives

This project was created to strengthen practical skills in:

* Backend development
* RESTful API design
* PostgreSQL database management
* Authentication and security
* Express.js architecture
* Git version control

## Author

Htin Zaw

GitHub: https://github.com/htinz

LinkedIn: https://www.linkedin.com/in/htin-zaw-7a21721a/
