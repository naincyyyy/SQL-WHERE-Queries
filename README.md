# SQL-WHERE-Queries
This repository contains  SQL queries using WHERE conditions from sales.employee table from the database created called SalesDB.
TABLE STRUCTURE
<code>

CREATE TABLE Sales.Employees 
(EmployeeID INT NOT NULL, FirstName VARCHAR(50), LastName VARCHAR(50), Department VARCHAR(50), BirthDate DATE, Gender CHAR(1), Salary INT, ManagerID INT, CONSTRAINT PK_employees PRIMARY KEY (EmployeeID));

INSERT INTO Sales.Employees
VALUES
    (1, 'Frank', 'Lee', 'Marketing', '1988-12-05', 'M', 55000, null),
    (2, 'Kevin', 'Brown', 'Marketing', '1972-11-25', 'M', 65000, 1),
    (3, 'Mary', null, 'Sales', '1986-01-05', 'F', 75000, 1),
    (4, 'Michael', 'Ray', 'Sales', '1977-02-10', 'M', 90000, 2),
    (5, 'Carol', 'Baker', 'Sales', '1982-02-11', 'F', 55000, 3);
    
  CONCEPTS PRACTICED:
- SELECT statement
- WHERE clause filtering
- AND conditions
- BETWEEN operator
- NULL handling
- Comparison operators
