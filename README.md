[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
# E-Commerce Back End

## Link to public repo on Github:

https://github.com/jcapadocia3/E-Commerce-Back-End

## Table of Contents
1. [Description](#Description)
2. [Final Product Image and Video Walkthrough](#Final-Product-Image-and-Video-Walkthrough)
3. [User Story](#User-Story)
4. [Installation and Instructions](#Installation-and-Instructions)
5. [License](#License)
6. [Questions](#Questions)

## Description
The purpose of this project is to allow a user to access and manipulate a database that hosts specific Product, Category, and Tag information of a store's stock. In this project, the user will have the option to create, read, update, and delete the information stored in the database as needed.

## Final Product Image and Video Walkthrough

- Image of final product created<br>
<img src="./assets/images/imgFile" alt="Final Product" width="600">

- Video walkthrough of how the project works via the command line<br>
    1) This video walkthrough below will demonstrate the application's GET routes to return both <b>ALL</b> and <b>SINGLE</b> categories, products, and tags.<br><br>
<a target="_blank" href="https://watch.screencastify.com/v/eDWVQaRu4GF3181AdBqW">Click Here</a>

    1) This video walkthrough below will demonstrate the application's POST, PUT, and DELETE routes for categories.<br><br>
<a target="_blank" href="https://watch.screencastify.com/v/YHyKnbeuixLvguY5cSZv">Click Here</a>

## User Story
```
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
```

## Installation and Instructions
- Download app files via GitHub
- In the ".env" file, change the "DB_USER" and "DB_PW" fields to your personal MySQL credentials
- Open GitBash/Terminal to access the command line
- Via the command line:
    - type/run "npm install" to install required dependencies for use
    - type/run "cd db/"
    - type/run "mysql -u root -p" and enter your MySQL password when prompted
    - type/run "source schema.sql"
    - type/run "use ecommerce_db"
    - type/run "exit"
    - type/run "cd ../"
    - type/run "node seeds/index.js"
    - type/run "nodemon server.js" to begin server execution/initialization
- Open Insomnia Core
    - Enter any route created via the written code in /routes/api directory
    - Utilize the GET, POST, PUT, DELETE functionality of Insomnia Core to view and manipulate the database as needed
    - Play around and discover how each route allows you to view and manipulate the database!

## License
- MIT License
- Copyright 2021

    Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
    
    The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
    
    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## Questions
- GitHub Profile: <a href="https://github.com/jcapadocia3">jcapadocia3</a><br>
- My Email: james.capadocia@gmail.com<br>
***Please feel free to contact me for more information***