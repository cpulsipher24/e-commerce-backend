
# Ecommerce Backend
    
![License](https://img.shields.io/badge/License-MIT-blue.svg)
    
## Description
This project is the backend for an e-commerce application. It provides a RESTful API for managing categories, products, and tags within the e-commerce system.
    
## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Questions](#questions)
    
## Installation
Clone the repository to your local machine and open in a code editor. If you haven't already, install node.js. Open your terminal and run the command npm install to install the dependencies for this project.

Repository Link: https://github.com/cpulsipher24/e-commerce-backend
    
## Usage
Start the server:

npm start

## Database Setup
1. Create a MySQL database.
2. Update the .env file with your database details:
DB_NAME='your_database_name'
DB_USER='your_database_user'
DB_PW='your_database_password'
3. Run the following command to create the necessary tables:
npm run seed

## API Routes
Categories:

GET all categories: /api/categories
GET a single category by ID: /api/categories/:id
POST a new category: /api/categories
PUT (update) a category: /api/categories/:id
DELETE a category: /api/categories/:id
Products:

GET all products: /api/products
GET a single product by ID: /api/products/:id
POST a new product: /api/products
PUT (update) a product: /api/products/:id
DELETE a product: /api/products/:id
Tags:

GET all tags: /api/tags
GET a single tag by ID: /api/tags/:id
POST a new tag: /api/tags
PUT (update) a tag: /api/tags/:id
DELETE a tag: /api/tags/:id

## Testing with Insomnia
To test the API routes, you can use Insomnia Core. The following routes are available:

Categories:

GET all categories
GET a single category by ID
POST a new category
PUT (update) a category
DELETE a category
Products:

GET all products
GET a single product by ID
POST a new product
PUT (update) a product
DELETE a product
Tags:

GET all tags
GET a single tag by ID
POST a new tag
PUT (update) a tag
DELETE a tag


## Walkthrough Video Link
https://watch.screencastify.com/v/xnXmftubevh9gfCN7PWz

## Contributing
This project is open to collaboration. If you want to contribute, fork the repository and feel free to add code and create a pull request for review. 
    
## Questions
For questions or concerns, please contact me through my [GitHub profile](https://github.com/cpulsipher24) or via email at collintpulsipher@gmail.com.
