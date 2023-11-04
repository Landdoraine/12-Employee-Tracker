# Employee Tracker
  
  [![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)]

## Description

The project is to create an application called Employee Tracker to build a command-line application from scratch to manage a company's employee database, using Node.js, Inquirer, and MySQL.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Credits](#credits)

## Installation

Install NodeJS, and install 'inquirer', 'mysql2', 'dotenv' packages.

## Usage

To run the application, in the correct location, Open integrated terminal and run'node index.js'.

## License

License: [ISC License (ISC)](https://opensource.org/licenses/ISC)

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)]


## Credits

https://www.npmjs.com/package/inquirer

https://www.w3schools.com/sql/sql_insert.asp

https://www.npmjs.com/package/dotenv

https://ascii-generator.site/t/

https://www.tutorialspoint.com/sql/sql-using-joins.htm

https://www.freecodecamp.org/news/javascript-promise-tutorial-how-to-resolve-or-reject-promises-in-js/

## Features

* Upon launching the application in the command line, users are presented with the following options:

  *View all departments
  *View all roles
  *View all employees
  *Add a department
  *Add a role
  *Add an employee
  *Update an employee's role
  *Update an employee's manager
  *View employees by manager
  *View employees by department
  *View department budget
  *Exit

* When selecting "View all departments," users are presented with a neatly formatted table displaying department names and their corresponding department IDs.

* Choosing "View all roles" provides users with information on job titles, role IDs, the associated department, and salary for each role.

* Opting for "View all employees" displays a well-structured table containing employee details, including employee IDs, first names, last names, job titles departments, salaries, and the managers to whom the employees report.

* Selecting "Add a department" prompts users to input the name of the department, which is then added to the database.

* If users choose "Add a role," they are prompted to provide the name, salary, and department for the new role, which is subsequently added to the database.

* Allows users to input an employee's first name, last name, role, and manager, and the system adds the employee to the database.

* When selecting "Update an employee's role," users are prompted to select an employee and specify their new role, with the system updating this information in the database.

* Opting for "Update an employee's manager" requires users to select an employee and choose a new manager, resulting in the system updating the information accordingly.

* "View employees by manager" prompts users to select a manager, and the system displays a list of all employees reporting to the chosen manager.

* "View employees by department" requires users to choose a department, and the system lists all employees within the selected department.

* When selecting "View department budget," users are prompted to choose a department, and the system displays the total sum of salaries for that department.

* Users can exit the application at any time by choosing "Exit."


