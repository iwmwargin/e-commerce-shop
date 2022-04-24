![License](https://img.shields.io/badge/License-MIT-yellow.svg)

# E-Commerce Shop

## Table of Contents

- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Languages](#languages)
- [Usage](#usage)
- [Link to URL](#live-url-link)
- [Contributors](#contributors)
- [Questions](#questions)
- [License](#license)

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

## Description

    E-Commerce Shop is the back end for an e-commerce site. It will allow you to retrieve, edit and delete items in your e-commerce shop.

## Languages

![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
<br>
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
<br>
![MySQL](https://img.shields.io/badge/mysql-%2300f.svg?style=for-the-badge&logo=mysql&logoColor=white)
<br>
![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)<br>
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)
<br>
![Insomnia](https://img.shields.io/badge/Insomnia-black?style=for-the-badge&logo=insomnia&logoColor=5849BE)
<br>

## Live URL Link

https://iwmwargin.github.io/e-commerce-shop/

## Usage

Clone the repo, then npm install MySQL, express, node, sequelize and dotenv. Create a .env file that contains the db name of ecommerce_db;, your user name and password. Run mysql by typing mysql -u root -p in your command line.  Enter your password then type source db/schema.sql. Next type use ecommerce_db in the command line. With the database in use, exit mysql and type npm run seed in the command line. Finally type node server into the command line and then open up Insomnia. Use Insomnia to test your routes.

## Contributors

Eric Wargin

## Screenshots

Image of Terminal
<img src="https://github.com/iwmwargin/employee-tracker/blob/main/assets/Employee.png">

Link to Video
<a href="https://drive.google.com/file/d/1BCPuPIA3QVhu9iREmF1tWr-ipe90e2O9/view?usp=sharing" target="_blank">Walk Through Video</a>

## Questions?

iwmwargin@gmail.com
<br>
https://github.com/iwmwargin

## License

This project is licensed under the MIT. Please see https://opensource.org/licenses/MIT for more details.
