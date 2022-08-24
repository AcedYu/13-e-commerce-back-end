# 13-e-commerce-back-end
This assignment was assigned by the U.C. Berkeley Extension Full-time Full Stack Flex Boot Camp.
This is assignment 13 forthe program. In this assignment I was tasked to build the back end for an e-commerce site by modifying the given starter code. I configured a working Express.js API to use Sequelize to interact with a MySQL database.

It contains notable features such as:
- protection of important login information using .env
- Connection to a mySQL database using Sequelize
- schema and seed commands that create and seed the database with test data
- Working GET, POST, PUT, and DELETE routes that correspond to being able to view, create, update, and delete data in the mySQL server.

Due: Thursday, April 29, 2021 11:59 PM

```js
const productData = [
  {
    product_name: 'Plain T-Shirt',
    price: 14.99,
    stock: 14,
    category_id: 1,
  },
  {
    product_name: 'Running Sneakers',
    price: 90.0,
    stock: 25,
    category_id: 5,
  },
  {
    product_name: 'Branded Baseball Hat',
    price: 22.99,
    stock: 12,
    category_id: 4,
  },
  {
    product_name: 'Top 40 Music Compilation Vinyl Record',
    price: 12.99,
    stock: 50,
    category_id: 3,
  },
  {
    product_name: 'Cargo Shorts',
    price: 29.99,
    stock: 22,
    category_id: 2,
  },
];
```

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Node.js is required.

### Installing
To install the necessary dependencies, run the npm installation command
```
npm install
```
Before launching the program you should also run the data seeding command
```
npm run seed
```

### Testing
There are no tests in this application, however there is the ability to run a development server with the watch command
```
npm run watch
```

### Usage
You can run the program on the command line with the following command:
```
npm start
```

## Video Demo
* [Video Demo Here](https://youtu.be/oKe5atvzhpw)

## Built With

* [Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
* [Node.js](https://nodejs.org/en/docs/)
* [mySQL](https://dev.mysql.com/doc/)

## Authors
AcedYu
- [Link to Github](https://github.com/AcedYu)
- [Link to LinkedIn](https://www.linkedin.com/in/alex-yu-3712811b9/)
