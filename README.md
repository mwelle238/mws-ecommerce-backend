# mws-employee-tracker
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
## Description

This application adds a mysql database to a webserver for an e-commerce store to track inventory.  It can easily be expanded upon to integrate with a sales platform to automatically remove items from inventory when they are sold, and add new items to the store when they are added to the database.  It could be expanded upon to store consumer feedback such as ratings and reviews for products.  The possibilities are endless!


## Table of Contents

1. [Installation](#Installation)
2. [Usage](#Usage)
3. [Contributors](#Contributors)
4. [License](#License)
5. [Questions](#Questions)
6. [Demo](#Demo)


## Installation

run ```npm i``` in the command line to install required modules.
run ```mysql -u root -p``` and enter password to enter the mysql shell.
run ```SOURCE db/schema.sql``` in the mysql shell to create the ecommerce_db.
exit mysql
run ```npm run seed``` to seed the ecommerce_db
run ```npm start``` to start the server


## Usage

open Insomnia and run get, post, put and delete routs on /api/categories/, /api/products/, and /api/tags/ to view, edit and create data in the database


## Contributors

This project was built by Michael Welle.
Resources used include node.js, npm, mysql2, express, dotenv, and sequelize


## License

MIT License

## Questions

Email: [michaelpwelle@gmail.com](mailto:michaelpwelle@gmail.com)

Github: [github.com/mwelle238](https://www.github.com/mwelle238)

## Demo

Demo: [Demo link](https://drive.google.com/file/d/12s3--r2IGa4ZWYbPz1ZP6rRj4UbxpZhT/view)

