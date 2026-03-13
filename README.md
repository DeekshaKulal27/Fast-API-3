# FastAPI Internship -- Assignment 1

## Student Details

Name: Deeksha\
Course: B.E -- Artificial Intelligence and Data Science\
Module: FastAPI

------------------------------------------------------------------------

## Assignment Description

This assignment demonstrates the implementation of CRUD APIs using
FastAPI.\
The application manages a simple product inventory system.

The APIs allow users to: - View all products - Add new products - Update
product details - Delete products - Retrieve product by ID - Generate
inventory audit summary - Apply category-based discounts

------------------------------------------------------------------------

## Technologies Used

-   Python
-   FastAPI
-   Uvicorn
-   Swagger UI

------------------------------------------------------------------------

## API Endpoints Implemented

### 1. Get All Products

GET `/products`\
Returns the list of all products with total count.

### 2. Add Product

POST `/products`\
Adds a new product to the inventory.

### 3. Update Product

PUT `/products/{product_id}`\
Updates product price or stock availability.

### 4. Delete Product

DELETE `/products/{product_id}`\
Removes a product from the inventory.

### 5. Get Product by ID

GET `/products/{product_id}`\
Returns details of a specific product.

### 6. Product Audit

GET `/products/audit`\
Returns inventory summary including: - total products - products in
stock - out-of-stock product names - total stock value - most expensive
product

### 7. Bulk Discount (Bonus)

PUT `/products/discount`\
Applies a discount to all products in a specific category.

Example: /products/discount?category=Electronics&discount_percent=10

------------------------------------------------------------------------

## Project Structure

YOUR_UNIQUE_INTERNID_FASTAPI\
└── ASSIGNMENT 1\
├── main.py\
├── README.md\
├── Q1_Output.png\
├── Q2_Output.png\
├── Q3_Output.png\
├── Q4_Output.png\
└── Q5_Output.png

------------------------------------------------------------------------

## Running the Project

Install dependencies:

pip install fastapi uvicorn

Run the server:

python -m uvicorn main:app --reload

Open Swagger UI:

http://127.0.0.1:8000/docs

------------------------------------------------------------------------

## Output

Screenshots of API responses are included in the assignment folder as
required for evaluation.
