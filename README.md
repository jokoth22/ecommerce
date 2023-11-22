# E-commerce Back End 

## Description
E-commerce Back End is a back end demo for an e-commerce site using Express.js API. It allows users to create, update, delete data, seed test data, and display API routes in formarred JSON using Sequelize, MySQL, and Insomnia Core.

## Installation

To set up the Employee Tracker application, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the project directory in your terminal.
3. Install necessary dependencies by running:
   ```
   npm install
   ```
4. Ensure that MySQL is installed on your machine. If not, install it from [MySQL's official website](https://www.mysql.com/).

## Usage

To use the E-commerce, follow these instructions:

1. Start the MySQL command-line tool and login:
   ```
   mysql -u root -p
   ```
2. Create and set up the database using the provided `schema.sql` file:
   ```
   SOURCE db/schema.sql;
   ```
   Optionally, use `seeds.sql` to populate the database with sample data.
      ```
   SOURCE db/seeds.sql;
   ```

3. Exit the MySQL command line tool:
   ```
   exit
   ```
4. Start the application by running:
   ```
   npm start
   ```
   open Insomnia Core
   ```
5. Use Insomnia Core to open API GET routes and test API POST, PUT, and DELETE routes.

## Features
- Add database name, MySQL username, and MySQL password
- Create and seed development database
- Create, update, and delete data in my database

## Demo
https://drive.google.com/file/d/15ndDtaLSHL_Q4CUQ3IvLgGzjOtwAg9lm/view

## Contributing

If you wish to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes and push to your branch.
4. Create a Pull Request for review and potential merge to the main project.

## License

This project is licensed under the MIT - see the [MIT License](https://opensource.org/licenses/MIT) for details
