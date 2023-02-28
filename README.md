# E-Commerce-Backend

# Description
The backend storage for an e-commerce website using sequelize models.

# Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [Acceptance Criteria](#acceptance-criteria)

# Installation
Run npm i to install dependencies.

# Usage
Enter mysql login info into .env file.
In the db/ directory login to the mysql enviroment and run SOURCE schema.sql.
Run npm start to create database tables and hit ctrl + c to shutdown server.
Run npm run seed to seed the database.
Run npm start once nore and the server will be ready to go.

# Acceptance Criteria
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

Video link: https://drive.google.com/file/d/1YR-ETwAnBBchnYuV2lhyWQPiwfRlBOC9/view
![image](https://user-images.githubusercontent.com/116223460/219267442-6d9588ac-af6e-46d3-a4b3-8a5248ebf213.png)
