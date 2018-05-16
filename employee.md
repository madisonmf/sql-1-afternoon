// Tables - Employee

SELECT FirstName, LastName FROM Employee
WHERE City = 'Calgary';

SELECT FirstName, LastName, Max(BirthDate) FROM Employee;

SELECT FirstName, LastName, Min(BirthDate) FROM Employee;

SELECT EmployeeID FROM Employee
WHERE FirstName = 'Nancy' AND LastName = 'Edwards';

SELECT * FROM Employee
WHERE ReportsTo = '2';

SELECT count(EmployeeID) from EMPLOYEE
Where City = 'Lethbridge';