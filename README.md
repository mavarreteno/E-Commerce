# E-Commerce Back End

## Description

This is the backend for your application, which serves as the server-side component responsible for handling API requests, managing data persistence, and communicating with the database. It is built using Node.js, Express.js, and Sequelize ORM to interact with the database.

## Available Endpoints

The backend provides the following API endpoints:

GET /api/categories: Get all categories with their associated products.

GET /api/categories/:id: Get a single category by its ID with its associated products.

POST /api/categories: Create a new category.

PUT /api/categories/:id: Update a category by its ID.

DELETE /api/categories/:id: Delete a category by its ID.

GET /api/products: Get all products with their associated categories and tags.

GET /api/products/:id: Get a single product by its ID with its associated categories and tags.

POST /api/products: Create a new product with optional tags.

PUT /api/products/:id: Update a product by its ID with optional tags.

DELETE /api/products/:id: Delete a product by its ID.

GET /api/tags: Get all tags with their associated products.

GET /api/tags/:id: Get a single tag by its ID with its associated products.

POST /api/tags: Create a new tag.

PUT /api/tags/:id: Update a tag by its ID.

DELETE /api/tags/:id: Delete a tag by its ID.

## Database Models

The backend uses the following Sequelize models to interact with the database:

### Category:

Represents the categories table in the database.

### Product: 

Represents the products table in the database.
### Tag:

Represents the tags table in the database.
### ProductTag: 

Represents the product_tags table in the database (join table for many-to-many relationship between products and tags).

## Walkthrough

Here you can watch a video that demonstrates the functionality of the CRUD operations:
(https://watch.screencastify.com/v/zWbaQKz4sePWReZG2liA)