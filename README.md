# E-Commerce-Back-End-Ch-13

## Description

This is the backend for an e-commerce website. It allows users to view, create, update, and delete products, categories, and tags. It uses Node.js, Express.js, Sequelize, and MySQL to store and manage data.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)

## Installation

1.  Clone the repository to your local machine.
2.  Open a terminal window and navigate to the root directory of the repository.
3.  Type "npm install" into the terminal window.
4.  Create a .env file in the root directory of the repository with the following variables:

        * DB_NAME='ecommerce_db'
        * DB_USER='root'
        * DB_PW='your MySQL password'

## Usage

Make sure you have MySQL installed on your computer. Then, follow these steps:

1. Type "CREATE DATABASE ecommerce_db;" into MySQL Workbench.
2. Open a terminal window and navigate to the root directory of the repository.
3. Type "npm run seed" into the terminal window.
4. Type "npm start" into the terminal window.
5. Use a tool like Insomnia or Thunder Client to test the routes.

## API Routes

### Categories

- GET /api/categories - Get all categories
- GET /api/categories/:id - Get a single category by its `id` value
- POST /api/categories - Create a new category
- PUT /api/categories/:id - Update a category by its `id` value
- DELETE /api/categories/:id - Delete a category by its `id` value

### Products

- GET /api/products - Get all products
- GET /api/products/:id - Get a single product by its `id` value
- POST /api/products - Create a new product
- PUT /api/products/:id - Update a product by its `id` value
- DELETE /api/products/:id - Delete a product by its `id` value

### Tags

- GET /api/tags - Get all tags
- GET /api/tags/:id - Get a single tag by its `id` value
- POST /api/tags - Create a new tag
- PUT /api/tags/:id - Update a tag by its `id` value
- DELETE /api/tags/:id - Delete a tag by its `id` value

## Video Walkthrough

https://drive.google.com/file/d/15N9QdK4HsHHCrLq4wHnX8FPkxYXFjkGE/view

## License

  <img src="https://img.shields.io/badge/license-MIT-blue.svg">
  
  This project is licensed under MIT;


## Contributing

This application was developed as a learning exercise, and is not actively maintained. However, if you would like to contribute to the project, feel free to fork the repository and submit a pull request.

## Questions

If you have any questions about the repo, open an issue or contact me directly at [email](hilltyler49@gmail.com). You can find more of my work at [GitHub](Tyler-Hill)
