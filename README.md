Product Inventory Management System
Project Overview
The Product Inventory Management System is a backend web application developed using Node.js, Express.js, and MongoDB.
The system provides RESTful APIs for managing product inventory with secure user authentication using JWT (JSON Web Token).
This project allows users to register, log in, and manage their product inventory by performing CRUD operations.
Technologies Used
Node.js – Backend runtime environment
Express.js – Web framework for building APIs
MongoDB – NoSQL database
Mongoose – ODM for MongoDB
JWT Authentication – Secure API access
bcryptjs – Password hashing
Thunder Client – API testing tool
Visual Studio Code – Development environment
Features
User Registration
User Login with JWT Authentication
Create Product
View All Products
Update Product Details
Delete Product
Secure API with Authentication Middleware
Each user can manage only their own products
Project Structure
Copy code

server
│
├── src
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── middlewares
│   ├── db
│   └── server.js
│
├── .env
├── package.json
└── node_modules
Environment Variables
Create a .env file inside the server folder.
Example:
Copy code

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
Installation and Setup
Clone the repository
Copy code

git clone <repository_link>
Navigate to the project folder
Copy code

cd server
Install dependencies
Copy code

npm install
Start the server
Copy code

npm start
The server will run on:
Copy code

http://localhost:5000
API Endpoints
Authentication APIs
Register User
Copy code

POST /api/v1/auth/register
Login User
Copy code

POST /api/v1/auth/login
Product APIs
Create Product
Copy code

POST /api/v1/products
Get All Products
Copy code

GET /api/v1/products
Update Product
Copy code

PUT /api/v1/products/:id
Delete Product
Copy code

DELETE /api/v1/products/:id
API Testing
All APIs were tested using Thunder Client inside Visual Studio Code.
Project Demo Video
Demo Video Link:
(Add your video link here)
Conclusion
The Product Inventory Management System provides a secure backend solution for managing product inventory using modern backend technologies and RESTful API architecture.
