# E-Commerce Backend Week 13
![License](https://img.shields.io/badge/license-GPLv3-blue)

Your Task
Internet retail, also known as e-commerce, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Due to their prevalence, understanding the fundamental architecture of these platforms will benefit you as a full-stack web developer.

Your task is to build the back end for an e-commerce site by modifying starter code. You’ll configure a working Express.js API to use Sequelize to interact with a MySQL database.

Because this application won’t be deployed, you’ll also need to provide a link to a walkthrough video that demonstrates its functionality and all of the acceptance criteria being met. You’ll need to submit a link to the video and add it to the readme of your project.

## User Story
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria
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

## Table of Contents
* [Installation](#installation)
* [Example](#example)
* [License](#license)
* [Questions](#questions)
* [Contributing](#contributing)
* [Tests](#tests)

## Installation
  1. ```npm init``` to install your package.json.
  2. ```npm i``` to install required dependencies.
  3. Please edit the .env.EXAMPLE with your local system information and change the file name to ```.env``` only
  4. Within the SQL prompt: Type ```source ./db/schema.sql``` to create the database
  5. In the normal terminal please run ```node seeds```
  6. You may now run npm start. This will start the server. You may now use insomnia or your preferred application for any CRUD operations. See the routes folder for correct routes. 

  ## Example

  [Video Link](https://drive.google.com/file/d/1tmfzDGFbg8nS78MdU9b2-HFXb6zXjr7u/view?usp=sharing)

  ## License
GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

Copyright (C) 2007 Free Software Foundation, Inc. <https://fsf.org/>
Everyone is permitted to copy and distribute verbatim copies
of this license document, but changing it is not allowed.

---
## Questions
If you have any questions or concerns reach me on [Github](https://github.com/SirNathanJF) or through email at <nathanflessner1@gmail.com>

## Contributing
    No contributions at this time.

## Tests
    No tests are currently being run.