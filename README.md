# E-Commerce RESTful API

## Description

This project is a RESTful API built with Flask for managing products in an e-commerce application. It provides endpoints for retrieving, creating, updating, and deleting products. The API persists product data in a MongoDB database and includes proper error handling and documentation for the endpoints.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/HKSIN1998/ecommerce-backend.git
    ```

2. Navigate to the project directory:

    ```bash
    cd ecommerce
    ```

3. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage
1. Run the Flask application:

    ```bash
    python run.py
    ```

2. Access the API endpoints using a REST client such as Postman.

## API Documentation

The API provides the following endpoints:

- `GET /api/products`: Retrieve a list of all products.
- `GET /api/products/{id}`: Retrieve details of a specific product by its ID.
- `POST /api/products`: Create a new product with JSON data.
- `PUT /api/products/{id}`: Update an existing product by its ID.
- `DELETE /api/products/{id}`: Delete a product by its ID.
