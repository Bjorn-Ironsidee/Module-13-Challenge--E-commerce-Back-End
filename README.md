# Module 13 Challenge: E-commerce Back End
 Module 13 Challenge: E-commerce Back End
# E-commerce Backend

This project is a backend application for an e-commerce site. It uses Express.js for the server, Sequelize as the ORM for interacting with a MySQL database, and provides API endpoints for managing categories, products, and tags.

## Installation

1. Clone the repository:

   ```bash
   git clone 
   
2. install dependencies:
cd ecommerce-backend
npm install

3. Set up the database:
Create a MySQL database and update the connection configuration in config/connection.js if necessary.
Run the database migration to create the tables:
npm run seeds

## Usage
1. Start the server with npm start.
2. Access the API endpoints using a tool like Postman or curl:
Categories:
GET /api/categories: Get all categories.
GET /api/categories/:id: Get a category by ID.
POST /api/categories: Create a new category.
PUT /api/categories/:id: Update a category by ID.
DELETE /api/categories/:id: Delete a category by ID.
Products:
GET /api/products: Get all products.
GET /api/products/:id: Get a product by ID.
POST /api/products: Create a new product.
PUT /api/products/:id: Update a product by ID.
DELETE /api/products/:id: Delete a product by ID.
Tags:
GET /api/tags: Get all tags.
GET /api/tags/:id: Get a tag by ID.
POST /api/tags: Create a new tag.
PUT /api/tags/:id: Update a tag by ID.
DELETE /api/tags/:id: Delete a tag by ID.