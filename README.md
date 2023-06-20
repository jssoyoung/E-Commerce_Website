# E-Commerce_Website

## Description

This project is the back end for an e-commerce website. The seeds contains all of the category names, product information, and tag information and the product-tag id. The models contain the different information that is saved for all the products, tags, and categories. The routes each has a get route to get all the category, product, or tag information or for just one. There is also a way for users to add, update, or delete a category, product or tag. This project contains notes in the database, models, routes, seeds, and server.js.

Here is the link to the github for this project: https://github.com/jssoyoung/E-Commerce_Website

Here is the link to the website demonstration video: https://drive.google.com/file/d/1GRq-YZsRzKppceHHctsn3YwREf7f5IeM/view

## Installation

The user will first be required to have a command-line application downloaded onto their computer or laptop. The user must also have node.js installed onto that device and a mysql username. Once they have these two downloaded, the user could type "npm i" into their terminal or window. This should install the dotenv, sequelize, express, and mysql package into the user's command-line application. Once these packages are finished being installed, the user can type in "mysql -u root" (add -p if the user has a password). The user should input their mysql username and password (if they have one). They will need to type "source db/schema.sql". They could then leave mysql and run the seeds using "npm run seeds". Finally, the user will need to type in npm start.

## Usage

The user should follow the installation steps listed above in order to run this project. Once the server is started using npm start, the user could then type in different routes to look at all the category, tag, and product information. The user could use the get request to grab a single category, tag or product using their id number. They could also get all the products, tags, or categories. The user could use the post request to create a new category, product, or tag. The put request will update an already existing category, product or tag. The delete request will delete an existing category, product, or tag. 

## Credits

N/A

## License

Please refer to the LICENSE in the repo.