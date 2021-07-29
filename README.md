![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
# E-Commerce back end application

Utilize express.js and sequelize to interact with a mySQL database that contains products, categories, tags, etc. 

## Table of contents
* [Description](#description)
* [Installation](#installation)
* [Usage](#usage)
* [License](#license)
* [Contributors](#contributors)
* [Tests](#tests)
* [Questions](#questions)

## Description

This backend application allows the user to get, add, edit, and delete categories, products, and tags from an e-commerce database.  The user will receive feedback based upon their queries if successful or given a failure.  Currently this application is able work on the following e-commerce tables:

<ol>
<li>Get ALL or a SINGLE product, tag, or product category</li>
<li>Edit a single product, tag, product category</li>
<li>Add a single product, tag, or product category</li>
<li>Delete a single product, tag, or product category</li>
<li>Receive a 404 error if the user queries an invalid product, tag, or product category id</li>

## Installation

Installations required: [node.js](https://nodejs.org/en/), [mysql](https://www.mysql.com/), [express.js](https://www.npmjs.com/package/express), [sequelize](https://www.npmjs.com/package/sequelize), [dotenv](https://www.npmjs.com/package/dotenv), [Insomnia](https://insomnia.rest/)

When cloning the files, complete an <code>npm i</code> in the terminal at the directory where the ```package.json``` is located.  Express, mysql2, dotenv, and sequelize packages will be installed for application use.  

Be sure to ```SOURCE schema.sql``` in mysql and run in the terminal ```node .seed/index.js``` to create and populate the e-commerce database (**ecommerce.db**). 

The user will need to create a ```.env``` file which contains
```
DB_NAME=ecommerce_db
DB_PASSWORD= your_password_here
DB_USER=root
``` 
and fill in their own mysql password.

The user will need Insomnia to modify the ecommerce database cells.

[GitHub link to repository](https://github.com/NguyenJohnnyT/e-commerce_backendr)


## Usage

After creating the **ecommerce_db** database after running ```SOURCE schema.sql``` in mysql, and populating the tables using ```node .seed/index.js``` in the terminal.

The user will then open insomnia and submit GET, PUT, POST, and DELETE requests to their desire.  A sample video containing different variations is below.

[Video link](https://streamable.com/sr2fw3)

## License

This application is licensed under [MIT]((https://opensource.org/licenses/MIT)).

## Contributors

Anyone can contribute to this project.

## Tests

No tests available.

## Questions
Have a question? Please email me at johnnytrucnguyen@gmail.com

[My Github](https://www.github.com/nguyenjohnnyt)