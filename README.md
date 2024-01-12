**Department Top Three Salaries**

Each row of the Employee table indicates the ID, name, and salary of an employee. It also contains the ID of their department.
id is the primary key (column with unique values) for this table.
departmentId is a foreign key (reference column) of the ID from the Department table.

Each row of the Department table indicates the ID of a department and its name.
id is the primary key (column with unique values) for this table.
A company's executives are interested in seeing who earns the most money in each of the company's departments. 
A high earner in a department is an employee who has a salary in the top three unique salaries for that department.
Write a solution to find the employees who are high earners in each of the departments.
Return the result table in any order.
