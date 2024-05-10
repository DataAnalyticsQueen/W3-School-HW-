# W3-School-HW-
W3 school HW SELECT * FROM Customers 
WHERE City LIKE '[!acf]%';
SELECT * FROM Customers 
WHERE Country IN ('Norway','France');
WHERE Country NOT IN ('Norway','France');
SELECT * FROM Products 
WHERE Price BETWEEN 10 and 20;
SELECT * FROM Products 
WHERE Price NOT BETWEEN 10 and 20;
//SELECT * FROM Products 
WHERE ProductName BETWEEN 'Geitost' AND 'Pavlova';
SELECT * FROM Customers 
WHERE City LIKE 'a%';
SELECT * FROM Customers 
WHERE City LIKE '%a';
SELECT * FROM Customers 
WHERE City LIKE '%a%';
SELECT * FROM Customers 
WHERE City LIKE 'a%b';
SELECT AVG(Price)
FROM Products;
SELECT AVG(column_name)
FROM table_name 
WHERE condition;
SELECT AVG(Price)
FROM Products 
WHERE CategoryID =1;
SELECT AVG(Price) AS [average price]
FROM Products;
SElECT * FROM Products 
WHERE price > (SELECT AVG(price)FROM Products);
SELECT AVG(Price)AS AveragePrice,CategoryID 
FROM Products 
GROUP BY CategoryID;
SELECT AVG(price)
FROM Products;
SELECT SUM(Price)
FROM Products;
SELECT * FROM Customers 
WHERE City LIKE 'a%';
SELECT * FROM Customers
WHERE City LIKE '%a';
SELECT * FROM Customers
WHERE City LIKE 'a%';
SELECT * FROM Customers 
WHERE City LIKE '%a';
SELECT * FROM Customers 
WHERE Customername LIKE 'a%';
SELECT column1,column2,..
FROM table_name 
WHERE column LIKE pattern;
SELECT * FROM Customers 
WHERE city LIKE 'L_nd_';
SELECT * FROM Customers 
WHERE city LIKE '%L%';
SELECT * FROM Customers 
WHERE CustomerName LIKE 'La%';
SELECT * FROM Customers 
WHERE CustomerName LIKE 'a%' OR CustomerName LIKE 'b%';
SELECT * FROM Customers 
WHERE CustomerName LIKE 'a%';
SELECT * FROM Customers 
WHERE CustomerName LIKE 'b%s';
SELECT * FROM Customers 
WHERE CustomerName LIKE '%or%';
SELECT * FROM Customers 
WHERE CustomerName LIKE 'a_%';
SELECT * FROM Customers 
WHERE Country LIKE 'Spain';
SELECT * FROM Customers 
WHERE City LIKE 'a%';
SELECT * FROM Customers 
WHERE City LIKE '%a';
SELECT * FROM Customers 
WHERE City LIKE '%a%';
SELECT * FROM Customers 
WHERE City LIKE 'a%b';
SELECT * FROM Customers 
WHERE City NOT LIKE 'a%';
SELECT * FROM Customers
WHERE City LIKE '_a%';
