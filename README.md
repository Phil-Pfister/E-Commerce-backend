# E-Commerce Backend
  -------------------
  ## Badges
  -------------------
  [![License: Unlicense](https://img.shields.io/badge/license-Unlicense-blue.svg)](http://unlicense.org/)  
  ## Table of Contents  
  ----------------------
  - [Description](#description) 
  - [Usage](#usage)  
  - [Installation](#installation)   
  - [Contributing](#contributing)  
  - [Questions](#questions)
  - [License](#license)
    

  ## Description  
  -------------------
  Creates and seeds a sql database using 'sequelize' npm dependency and uses api methods to interact with data using GET, POST, PUT and DELETE methods. Data is returned in JSON and can be viewed using an API testing app like Insomnia.

  ## Usage  
  ------------
  After installation, seed the database by running `npm run seed` After seeding run `npm start` to start the server. 
 
  ## Installation  
  -------------------
  Clone the repo to your machine and run `npm i` to install node modules and dependencies. Copy .envEXAMPLE and paste into main file and rename .env. Supply login information in the .env file.  Run `mysql -u root -p ` and run `source db/schema to create database.

  ## Credits 
  ------------------
  I used the knowledge I learned in the Rice University Bootcamp class as well as documentation from 
  [mdn docs](https://developer.mozilla.org/en-US/) and [sequelize](https://sequelize.org/docs/v6/core-concepts/model-basics/). I also refered to [Stackoverflow](https://stackoverflow.com/) for suggestions on async javascript syntax.

  ## Tests
  ------------------
  Go to an API testing application like [Insomnia](https://insomnia.rest/) and run the routes: localhost:3001/api/categories, localhost:3001/api/products and localhost:3001/api/tags.

  ## Contact Information
  -------------------------
  ### Github: [Phillip Pfister](https://github.com/Phil-Pfister)
  ### Email: salshouse@gmail.com

  
  ## License 
-------------- 
This application uses the The Unlicense license
  

