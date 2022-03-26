# E-commerce Back End Template
With the growth of e-commerce, wouldn't it be nice to have a completed back end that just 'works'? This codebase contains routes and models for products, categories, tags, and product tags to start any e-commerce store get up and running. Easy to download and integrate, with an organized codebase and easy to follow code, this will become your new favorite tool.
<br><br>
Created with Node.js and Express.js with MySQL middleware from Sequelize.
<br>

## 🚚 Getting it up and running
** This requires SQL to be installed and set up first **
1. Clone the codebase from the [repo](https://github.com/mpityo/ecommerce-backend).
2. Query to the root file directory in any command prompt
3. Run the following command to install required packages:
```
npm install
```
4. Create a <heavy>.env</heavy> file in the root of the folder and input the following:
```
DB_NAME='ecommerce_db'
DB_USER='username'
DB_PW='password'
```
5. Make sure to change the username and password to your MYSQL information
6. Open mysql through the cmd line:
```
mysql -u root -p
```
7. Run schema to create database and tables:
```
SOURCE db/schema.sql;
quit;
```
8. (OPTIONAL) Seed the database to create mock data
```
npm run seed
```
9. Start the server:
```
npm start
```
You may view routes using your favorite program (Insomnia, Postman), or integrate into a front end for full functionality.
<br>
Want to see a walkthrough of the program? [Click here](https://drive.google.com/file/d/1GtcQSlGh4csnEUA050Yso2DISGXAh2cC/view?usp=sharing) for a google drive display.

## :memo: Features
 - Full api routing and MySQL integration using Sequelize
 - Environmental variables set up to protect your database information
 - Clean and organized for any developer
 - Full CRUD functionality for all routes
 
## :trophy: Credit
Project idea and starter code by @UCFBootCampt
<br>
Routes, models and functionality done by yours truly, @mpityo
<br>
<br>
Project is fully open source: explore the code and upgrade away!
<br>
<br>