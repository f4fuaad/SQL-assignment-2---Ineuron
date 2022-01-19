# SQL-assignment-2---Ineuron

Q-1. Write an SQL query to print the first three characters of  FIRST_NAME from Worker
table.
Ans:    Select  left(FIRST_NAME,3)
        from worker  table
 Q-2. Write an SQL query to find the position of the alphabet (‘a’) in the first name
column ‘Amitabh’ from Worker table.

Ans:    Select charindex (‘a’,first name)
        from worker  table
 
Q-3. Write an SQL query to print the name of employees having the highest salary in each
department.

Ans:  Select department, employee_name, Max(salary)
      from worker table
      group by employee_name, department,
