# E-Commerce Wizzard

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
    - single tag
- Test all POST, PUT, DELETE routes:
    - categories
    - products
    - tags