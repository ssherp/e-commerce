# e-commerce

## Description 
I've developed this application to demonstrate my understanding of backend web development using popular tools like Express.js and Sequelize ORM. The application allows users to manage products, categories, and tags in an inventory system. It provides API endpoints for performing CRUD (Create, Read, Update, Delete) operations on products, categories, and tags, along with their associated relationships.

[visit the Demo video](https://drive.google.com/file/d/1rAKb5UUVyJkxbrnj5R4xtuVwuOj_3Apj/view)

## Features
* *CRUD Operations*: Perform Create, Read, Update, and Delete operations for products, categories, and tags.
* *Associations*: Utilize Sequelize associations to establish relationships between products, categories, and tags.
* *Many-to-Many Relationship*: Implement a many-to-many relationship between products and tags using a junction table.
* *Express Routes*: Organize routes into separate modules for better maintainability.
* *Data Seeding*: Seed initial data for categories, products, tags, and their relationships.
* *Server Sync*: Sync Sequelize models with the database and start an Express server.

## Technologies Used
* *Node.js*: JavaScript runtime used for building server-side applications.
* *Express.js*: Web application framework for building APIs and handling routes.
* *Sequelize*: Promise-based ORM for interacting with relational databases.
* *MySQL*: Relational database management system used for data storage.
* *npm*: Package manager for installing and managing project dependencies.

## Getting Started
To get started with the application, follow these steps:

* Clone the repository to your local machine: git clone <repository-url>
* Navigate to the project directory
* Install the dependencies: npm install
## Usage
1. Configure your database settings in config/connection.js.
2. Run database migrations: npm run db:migrate
3. Seed the database with initial data: npm run db:seed
4. Start the server: npm start
5. Access the API endpoints through a tool like Postman or use them in your frontend application.

## Contact
* GitHub: https://github.com/ssherp/
* Email: ssherpa89@gmail.com

