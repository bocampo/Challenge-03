I created an Employee Payroll Tracker using the following criteria:

GIVEN an employee payroll tracker
WHEN I click the "Add employee" button
THEN I am presented with a series of prompts asking for first name, last name, and salary
WHEN I finish adding an employee
THEN I am prompted to continue or cancel
WHEN I choose to continue
THEN I am prompted to add a new employee
WHEN I choose to cancel
THEN my employee data is displayed on the page sorted alphabetically by last name, and the console shows computed and aggregated data
```

I also edited the displayAverageSalary() and getRandomEmployee() functions to do the following:

WHEN I as the user no longer wish to add more employees to the table
THEN I am presented with the average of employee salaries
WHEN the average salary is calculated and logged to the console
THEN I am presented with the employee's first and last name who won the random draw selection in the console