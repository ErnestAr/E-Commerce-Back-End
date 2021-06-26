# E-Commerce Back End
 Back End development for basic E-commerce 


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)
- [Features](#features)
- [How to Contribute](#how-to-contribute)
- [Tests](#tests)
- [Questions](#questions) 

## Installation 

N/A

## Usage 

Launch the file in your through your terminal and make sure to set the right README file in the write File function

## Credits 

## License 

[MIT](https://choosealicense.com/licenses/mit/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Features
1. When user runs db file code in the SQL workbench, database is created.
2. When user sets up root name, password and db name in env file and runs command: "npm run seed" in the terminal, DB is populated with data.
3. When user runs command: "npm run start", server.js is executed and back end server starts to run.
4. When user uses address: http://localhost:3001/api/categories, http://localhost:3001/api/tags, http://localhost:3001/api/products, in Insomnia or Postman GET request, correlating model shows up in a json format, where tags have related products, categories have related products and products have related tags and categories.
5.  When user uses address: http://localhost:3001/api/categories/:id, http://localhost:3001/api/tags/:id, http://localhost:3001/api/products/:id, in Insomnia or Postman GET request, item  (product, tag, category) with request id gets displayed.
6. When user When user uses address: http://localhost:3001/api/categories/:id, http://localhost:3001/api/tags/:id, http://localhost:3001/api/products/:id, in Insomnia or Postman PUT or DELETE request, item( (product, tag, category) with request id gets updated or deleted.
7. 6. When user When user uses address: http://localhost:3001/api/categories, http://localhost:3001/api/tags, http://localhost:3001/api/products, in Insomnia or Postman POST request, item (product, tag, category) with entered parameters is created.
## How to Contribute 

Create a pull request with description of added changes

## Tests 

N/A


## Questions 

[GitHub](https://github.com/ErnestAr)

email: arutiunian.ernest@gamil.com
