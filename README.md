# Zach's ecommerce site

#### By Zach Hanson and UTSA

## Description

My challenge this week was to build the back end for an e-commerce site. I was given a working Express.js API and instructed to configure it to use Sequelize to interact with a MySQL database. Testing was completed in Insomnia. The application will not be deployed, so a video walkthrough is provided below.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
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
```

## SnapShots

<img src="./Assets/Product.png" alt="Product" title="Product">
<img src="./Assets/Create.png" alt="Create" title="Create">
<img src="./Assets/CRUD.png" alt="CRUD" title="CRUD">

## Video Walkthrough

### Starting the application

<img src="./Assets/start-application.gif" alt= "Demo Video" title="Demo Video">

### GET routes: all Products, all Categories and all Tags

<img src="./Assets/Get.gif" alt= "Demo Video" title="Demo Video">

### Create, Update, Delete

<img src="./Assets/CRUD.gif" alt= "Demo Video" title="Demo Video">

## Technologies Used

JavaScript, mysql, database, sequelize, express-js,
insomnia, object-relational-mapping

## Website

Check out more of my work at https://github.com/ZachITP

## License

MIT Copyright (c) 2023 Zach Hanson

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
