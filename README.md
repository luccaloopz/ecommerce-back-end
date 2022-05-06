# E-commerce Store Back-end

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

## **Description**
The purpose of this project was to modify some starter code to essentially create the back end of an ecommerce store. In order to interact with the database, the Sequelize ORM was used.

## **Technologies**

* ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
* ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
* ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB)
* ![NPM](https://img.shields.io/badge/NPM-%23000000.svg?style=for-the-badge&logo=npm&logoColor=white)
* ![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=Sequelize&logoColor=white)

## **Installation**
First, you'll want to clone down this repository onto your local machine. You can do this by copying the code within the green code button towards the upper-righthand side of the screen and typing out `git clone *insert your copied code here*` within your command terminal.

Next, you'll want to type the following in the command line. This installs the dependencies that will be used. 
```
npm install
```

You'll want to have downloaded MySQL. If so, type the following into the command line: 
```
mysql -u root -p
```

Next, type the following when prompted for a password:
```
password
```

Next, you'll want to copy everything within the `schema.sql` file and paste it within the MySQL shell. Hit the `enter` key when done. (*note* = make sure you don't already have a database called "ecommerce_db" within your MySQL shell or else it will get deleted. Similarly, you can ommit line 2 from within `schema.sql` and simply change the name of the database on line 5 to whatever you'd like the database to be called.)

Next, type in the following to exit the MySQL shell:
```
exit
```

Next, type the following into the command line to seed your database:
```
npm run seed
```

Lastly, you'll want to run Node to start the application. You can do this by typing the following within the command line at the root of this project directory.
```
node server
```

## **Application**
The following is a link to a video walkthrough of the application: 
[![Video Walkthrough](./assets/Untitled_%20May%205%2C%202022%208_09%20PM.webm)](https://drive.google.com/file/d/1SuU1CTm_aZV1JQMh7s-neGvZ-m-jh5Ra/view "Video Walkthrough")

## **License**
The following application is covered under the MIT License.