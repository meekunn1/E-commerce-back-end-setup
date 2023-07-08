# E-Commerce-Back-End-Setup

## Description

This project is a setup for the database of an E-commerce application. The database consists of several models that are connected to each other and each with their CRUD routes. It uses [mySQL](https://www.mysql.com/) for database with [npm mysql2](https://www.npmjs.com/package/mysql2), and the CRUD operation can be checked using [Insomnia](https://insomnia.rest/). This project allowed me to practice data manipulation using [sequelize](https://www.npmjs.com/package/sequelize?activeTab=readme).

## Table of Contents

- [E-Commerce-Back-End-Setup](#e-commerce-back-end-setup)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Tests](#tests)
  - [Credit](#credit)
  - [Questions](#questions)

## Installation

First you will need to fill out the content for .env.EXAMPLE and have it renamed to .env. Next, please run mysql and run "SOURCE db/schema.sql;" to create mySQL database. Lastly you will need to seed the database by going to terminal and run "node seeds/index.js"

## Usage

To start the application, go to terminal and run "node server.js". Once you see an message in termanal that states "App listening to port 3001!", please open Insomnia to perform CRUD operation on following routes:
"http://localhost:3001/api/categories/"
"http://localhost:3001/api/products/"
"http://localhost:3001/api/tags/"

Please go to my [googledrive video link](https://drive.google.com/file/d/10yA-u9myrIPmrIn6PrufeKq6YP_s5b5Z/view) for a video demonstration of this application.

## License
  
[![license](https://img.shields.io/badge/License-MIT-green)](https://choosealicense.com/licenses/mit/)

## Tests

[Insomnia](https://insomnia.rest/) was used to test the functionality of all CRUD routes for this application.

## Credit

Starter code was provided by UCI bootcamp.
[Gitlab UCI-Coding-Bootcamp](https://uci.bootcampcontent.com/UCI-Coding-Bootcamp/UCI-VIRT-FSF-PT-03-2023-U-LOLC/-/tree/main/13-ORM/02-Challenge)
## Questions

For any questions, please visit my [GitHub profile](https://github.com/meekunn1).

For any additinal questions, please contact me through email at: meekunn@gmail.com