# Employee Database Management System

## Description

The **Employee Database Management System** is a command-line application designed to help business owners efficiently manage their company's departments, roles, and employees. This application uses **Node.js**, **Inquirer**, and **PostgreSQL** to create, view, and update information in the company's employee database. It provides an easy-to-use interface for viewing data and performing database operations like adding new departments, roles, and employees or updating employee roles.

## User Story

As a business owner,  
I WANT to be able to view and manage the departments, roles, and employees in my company,  
SO THAT I can organize and plan my business.

## Acceptance Criteria

- **GIVEN** a command-line application that accepts user input:  
  - **WHEN** I start the application,  
    - **THEN** I am presented with the following options:  
      - View all departments  
      - View all roles  
      - View all employees  
      - Add a department  
      - Add a role  
      - Add an employee  
      - Update an employee role  
  - **WHEN** I choose to view all departments,  
    - **THEN** I am presented with a formatted table showing department names and department IDs.  
  - **WHEN** I choose to view all roles,  
    - **THEN** I am presented with the job title, role ID, the department the role belongs to, and the salary for that role.  
  - **WHEN** I choose to view all employees,  
    - **THEN** I am presented with a formatted table showing employee IDs, first names, last names, job titles, departments, salaries, and managers that the employees report to.  
  - **WHEN** I choose to add a department,  
    - **THEN** I am prompted to enter the name of the department, and that department is added to the database.  
  - **WHEN** I choose to add a role,  
    - **THEN** I am prompted to enter the name, salary, and department for the role, and that role is added to the database.  
  - **WHEN** I choose to add an employee,  
    - **THEN** I am prompted to enter the employee's first name, last name, role, and manager, and that employee is added to the database.  
  - **WHEN** I choose to update an employee role,  
    - **THEN** I am prompted to select an employee to update and their new role, and this information is updated in the database.  

## Installation

1. Clone the repository to your local machine:  
   ```bash
   git clone https://github.com/realdanielsoto/modc12.git
