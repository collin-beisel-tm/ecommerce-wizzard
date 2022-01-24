# E-Commerce Wizzard

 ![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

 ## Table of Contents
  * [Links](#links)
  * [Description](#app-descriptino)
  * [Technologies Used](#technologies-used)
  * [Why I Built](#why-did-i-build-this-project)
  * [What I learned](#what-did-i-learn)
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Tests](#tests)
  * [User Story](#User-Story)
  * [Acceptance Criteria](#acceptance-criteria)

![Insomnia Screenshot](https://github.com/collin-beisel-tm/ecommerce-wizzard/blob/main/assets/screenshot.PNG)

## Links
 - Github Repo: https://github.com/collin-beisel-tm/ecommerce-wizzard
 - Video Demo: https://drive.google.com/file/d/1cUzFrElHGHZgSNYl0jQalPQE2Ulrn72G/view?usp=sharing
## App Description

E-Commerce Wizzard is a back end application that supplies product data to front end ecommerce sites. it was built using MySQL2, Express, and javascript.

## Technologies used
- JavaScript
- Node.js
- Express.js
- MySQL2
- Sequelize
- Git/GitHub

## Why did I build this project?
I built this project as a bootcamp assignment. 

## What did I learn?
This project taught me how to use MySQL to create a database using Sequelize.js and use express.js to write routes to the database.

## Installation
 - Navigate to https://github.com/collin-beisel-tm/ecommerce-wizzard
 - click the download/clone the package
 - Open with your favorite code editor
 - Run NPM i
 - update your mysql credentials in the .env file
 - SOURCE your schema and seeds files
 - run npm start in your terminal
 - The app will start
 - Hit routes through postman/insomnia
## license
MIT License

Copyright (c) [2021] [CollinBeisel]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
## User Story
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business

## User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database


Video Walk Through Points to hit:
- Show .env file
- show connection.js file and sequelize connection
- show how to SOURCE the schema.db file
- show how to seed the db npm run seed
- start the server npm start
- Test GET ALL routes:
    - categories
    - products
    - tags
- Test all GET ID routes:
    - single category
    - single product
    - single taga
- Test all POST, PUT, DELETE routes:
    - categories
    - products
    - tags