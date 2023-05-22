# E-Commerce Back End

![License](https://img.shields.io/badge/license-MIT-green)

## Description
This is a node run application that allows a user to manage a mysql database of products.

Future development would be deploying it through Heroku.
    
## Table of Contents 
    
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [Tests](#tests)
- [Questions](#questions)
- [License](#license)

    
## Installation
- Node v16
- MySQL
- Insomnia
    
## Usage
To use this application, you must:
1. Download this repositiory to your local machine.
2. In the terminal, launch mysql by typing:

        mysql -u root -p
3. Enter your local password.
4. Input the following:

        source db/schema.sql
5. Open a new terminal and seed the database by typing:

        npm run seed
6. To download the dependencies by typing: 

        npm i
    This will install the npm packages dotenv, express, mysql2, and sequelize.
  
7. Create a copy of the .env.EXAMPLE file, rename it to .env, and add your mysql user and password.
8. To run the app, type:

        npm start
9. Open Insomnia and run the routes as you please at the specified port.

[DEMO Employee Tracker.webm](https://github.com/ctalv/employee-tracker/assets/122413805/daed602e-191c-4af0-a0ec-bd6bd90d0a5e)

 
## Credits
N/A


## Tests
N/A
    

## Questions
If you have any questions, email me at clairetalverson@gmail.com or message me on my GitHub at https://github.com/ctalv.

## License
This project is covered under the MIT License.
