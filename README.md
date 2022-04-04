# ORM-ecommerce

# Description

Build for back end e-commerce site. Express.js API's will use Sequelize to interact with MYSQL database of inventory. I begin this process by entering MYSQL credentials, connecting the database to Sequelize, seeding my SQL data and finally manipulate data through Insomnia API routes.


## Installation

You will need to `npm i` and install the following packages: `npm install express`, `npm install mysql2`, `npm install sequelize`, `npm install dotenv`.


# Usage

 **MYSQL**
1. You will need to add or rename `.env` file and add 
    `DB_NAME='ecommerce_db'`
    `DB_USER='root'`
    `DB_PW='toor'`.   
2. Run `mysql -u root -p` with entered credentials. 
3. Run source db/schema.sql
4. Quit mysql

**Server.js**
1. Run `npm run seed` to seed the database.
2. Run `npm start`.


## Mock up & Visual

Please see walkthrough video [here]()

![example image](./Assets/13-orm-homework-demo-01.gif)

## Contact / Questions

- [Email](elorrainemitchell@gmail.com)
- [GitHub Repo](https://github.com/ericaLorraineMitchell/orm-ecommerce.git)
