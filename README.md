# E-Commerce Back-End

## Description

Back-end for an e-commerce app. Uses sequelize to interact with MySQL DB.

[Github Repository](https://github.com/JPablo73/E-Commerce-Back-End)

## Table of Contents

- [User Story](#userstory)

- [Technologies](#technologies)

- [Installation](#installation)

- [Usage](#usage)

- [Demo](#demo)

- [Questions](#questions)

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Technologies

- [MySQL2](https://www.npmjs.com/package/mysql)

- [Sequelize](https://www.npmjs.com/package/sequelize)

- [dotenv](https://www.npmjs.com/package/dotenv) package

## Installation

To install dependencies, run:

```bash
npm install
```

## Usage

Use the schema.sql file in the db folder to create your database with MySQL shell commands. Copy and paste the following to MySQLWorkbench;

```bash
-- DROP DATABASE
DROP DATABASE IF EXISTS ecommerce_db;

-- CREATE DATABASE
CREATE DATABASE ecommerce_db;
```

seed the db with the following command on your VS Code terminal:

```bash
npm run seed
```

Start the server. Run the following command in the VS Code terminal:

```bash
npm start
```

Ready to make request commands to your server!

## [Demo](https://watch.screencastify.com/v/lWga91a8McjUvU28KI3I)

## Questions

For quetions and/or suggestions, you may reach me at bernal1307@gmail.com / [Github](https://github.com/JPablo73/).
