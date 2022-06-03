# ECommerceBackend

[![License: Apache](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Description

The motivation for this project was to implement the backend of an E-Commerce system using the package Sequelize to be testable with an application like Postman or Insomnia. I utilized Express.js for my middleware and used Node as the package manager. Potentially in the future I would like to make a user interface for this application rather than just a backend implementation. With the completion of this project I fulfilled the following user story and acceptance criteria.

[Video of Functioning Application](https://drive.google.com/file/d/1JVjMq3okLjP7JDPnsIwYb503PJ9IhpSW/view)

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

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)

## Installation

Set up a local .env file with your mysql user and password by using the .env.EXAMPLE file provided. You will need an instance of MySQL installed so that you can run this locally. Run the following command in order to be able to install the package for this code:

    npm install

## Usage

To run this code from the parent directory after setup use the following commands:

    mysql -u root -p -> enter in your password for mysql within the prompt
    source db/schema.sql
    \q
    npm run seed
    npm start

## License

This project is covered under the following license: [![License: Apache](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

## Contributing

To contribute to this project please clone the repo locally and commit your code using a separate branch. Please have unit tests for your code and make sure all tests pass using the test command before opening a pull request.

## Questions

If there are any questions on the work provided in this repository please use the following contact information:

GitHub: [heatherknoyes](https://github.com/heatherknoyes)

Email: heatherknoyes@gmail.com
