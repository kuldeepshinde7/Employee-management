# Employee_management_system
Employee management system built using Flask for the web framework and MySQL for the database. Here's a summary of the features and functionality of project:

User Authentication:

A simple login system where the admin can log in with a username and password. The session is managed using Flask's session feature.
Logout functionality clears the session.
Adding Employees:

Admin can add employee details (name, position, and department) via a form. These details are saved in the MySQL database.
Removing Employees:

Admin can remove an employee based on their ID. Before removal, the employee's data is moved to a separate table (removed_employees) for record-keeping.
Promoting Employees:

Admin can promote employees by updating their position and department. The updates are reflected in the MySQL database.
Displaying Employees:

Admin can search for employees by their position, displaying the results from the database.
Routing Structure:

There are specific routes for login (/), logout (/logout), adding employees (/add_employee_page, /add_employee), removing employees (/remove_employee_page, /remove_employee), promoting employees (/promote_employee_page, /promote_employee), and displaying employees (/display_employee_page, /display_employee).
Database Interaction:

MySQL is used to store, update, and retrieve employee data, using SQL queries within Flask's request handlers.
This project offers a streamlined way to manage employee records and operations within a company.
