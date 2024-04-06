# Ecommerce API

This repository contains an API for managing product inventory for an ecommerce platform admin. The API is designed using Node.js and MongoDB. You can use Postman to test the API endpoints.

# Setup

To set up the project on your local system, follow these steps:

1. Clone the repository :
   git clone <repository_url>

2. Navigate to the project directory:
   cd ecommerce-api

3. Install dependencies:
   npm install

4. Set up your MongoDB database and configure the connection string in config.js.

5. Start the server:
   npm start

# API Endpoints

1. Add Products
  - URL: POST /products/create

2. List Products
  - URL: GET /products

3. Delete Products
  - URL: DELETE /products/:id

4. Update Quantity of a Product
  - URL: POST /products/:id/update_quantity/?number=10
