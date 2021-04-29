<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/doctypehuman/sql">
    <img src="images/logo.jpeg" alt="Logo" width="1200" height="400">
  </a>

  <h3 align="center">Fundamentals Of SQL</h3>

  <p align="center">
    One Pager for SQL Fundamentals!
    <br />
    <br />
    ·
    <a href="https://github.com/doctypehuman/sql/issues">Report Bug</a>
    ·
    <a href="https://github.com/doctypehuman/sql/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ul>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li>
	<a href="#module-1">Module 1</a>
	<ul>
	<li><a href="#introduction-to-sql">Introduction To SQL</a></li>
	<li><a href="#Syntax">Syntax</a></li>
	<li><a href="#Select">Select</a></li>
	<li><a href="#Select-Distinct">Select Distinct</a></li>
	</ul>
    <li><a href="#Module-2">Module 2</a></li>
	<ul>
	<li><a href="#Where-Clause">Where Clause</a><li>
	<li><a href="#And-Or-Not">And Or Not</a></li>
	<li><a href="#Order-By">Order By</a></li>
	</ul>
    <li><a href="#Module-3">Module 3</a></li>
	<ul>
	<li><a href="#Insert-Into-Statement">Insert Into Statement</a></li>
	<li><a href="#Null-Values">Null Values</a></li>
	<li><a href="#Update-Statement">Update Statement</a></li>
	<li><a href="#Delete-Statement">Delete Statement</a></li>
	</ul>
    <li><a href="#Module-4">Module 4</a></li>
	<ul>
	<li><a href="Top-Limit-Row-Num">Top Limit Or Row Num</a></li>
	<li><a href="basic-functions">Basic Functions</a></li>
	<li><a href="Like-Operator">Like Operator</a></li>
	<li><a href="Wildcards">Wildcards</a></li>
	<li><a href="In-Operator">In Operator</a></li>
	<li><a href="Between-Operator">Between Operator</a></li>
	<li><a href="Aliases">Aliases</a></li>
	</ul>
    <li><a href="#Module-5">Module 5</a></li>
	<ul>
	<li><a href="#Joins">Joins</a></li>
	<li><a href="#Inner-Join">Inner Join</a></li>
	<li><a href="#Left-Join">Left Join</a></li>
	<li><a href="#Right-Join">Right Join</a></li>
	<li><a href="#Full-Outer-Join">Full Outer Join</a></li>
	<li><a href="#Self-Join">Self Join</a></li>
	<li><a href="#Union-Operator">Union Operator</a></li>
	</ul>	
    <li><a href="#Module-6">Module 6</a></li>
	<ul>
	<li><a href="#Group-By-Statement "> Group By Statement</a></li>
	<li><a href="#Having-Clause">Having Clause</a></li>
	<li><a href="#Exists-Operator">Exists Operator</a></li>
	<li><a href="#Any-and-All-Operators">ANY and ALL Operators</a></li>
	<li><a href="#Select-Into-Statement">Select Into Statement</a></li>
	<li><a href="#Insert-Into-Select-Statement">Insert Into Select Statement</a></li>
	<li><a href="#Case-Statement">Case Statement</a></li>
	<li><a href="#Null-Functions ">Null Functions</a></li>
	</ul>
    <li><a href="#Module-7">Module 7</a></li>
	<ul>
	<li><a href="#Stored-Procedure">Stored Procedure</a></li>
	<li><a href="#Comments">Comments</a></li>
	<li><a href="#Operators">Operators</a></li>
	</ul>
    <li><a href="#Module-8">Module 8</a></li>
	<ul>
	<li><a href="#Create-Database">Create Database</a></li>
	<li><a href="#Drop-Database">Drop Database</a></li>
	<li><a href="#Backup-Database">Backup Database</a></li>
	<li><a href="#Create-Table">Create Table</a></li>
	<li><a href="#Alter-Table">Alter Table</a></li>
	<li><a href="#Constraints">Constraints</a></li>
	<li><a href="#Not-Null-Constraints">Not Null Constraints</a></li>
	<li><a href="#Unique-Constraint">Unique Constraints</a></li>
	<li><a href="#Primary-Key-Constraint">Primary Key Constraint</a></li>
	<li><a href="#Foreign-Key-Constraint">Foreign Key Constraint</a></li>
	<li><a href="#Check-Constraint">Check Constraint</a></li>
	<li><a href="#Default-Constraint">Default Constraint</a></li>
	<li><a href="#Create-Index-Statement">Create Index Statement</a></li>
	<li><a href="#Auto-Increment-Field">Auto Increment Field</a></li>
	<li><a href="#Working-With-Dates">Working With Dates</a></li>
	<li><a href="#Views">Views</a></li>
	<li><a href="#Injection">Injection</a></li>
	<li><a href="#Hosting">Hosting</a></li>
	<li><a href="#Data-Types">Data Types</a></li>
	</ul>

  </ul>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

 In the process of learning something, it is best if you can reproduce what you learnt. Keeping this mantra in mind, I have decided to share what I have learnt about SQL Fundamentals. The project is broken into modules. Each module has different topics that are covered. I will try to include exercises that I have come across as a reference for you. As of now please consider that to be out of scope. For free exercises you can check out [W3Schools.](www.w3schools.com) That is where I have learnt the basics. I am passing on all of the information so that you do not have to pay to learn. You might still need to pay for a certificate but if you are just starting out and want to get notes, this project should suffice.




<!-- GETTING STARTED -->
## Getting Started

You can use this project to learn SQL either on a MYSQL server or a POSTGRESQL server. The database that is used as an example is Northwinds Databse. This is an example database that Microsoft created for tutorials. It is available on GitHub [here.](https://github.com/Microsoft/sql-server-samples/tree/master/samples/databases/northwind-pubs)

For a POSTGRESQL server the database that can be used is the DVD Rental Database that can be found [here.](https://sp.postgresqltutorial.com/wp-content/uploads/2019/05/dvdrental.zip)

### Prerequisites

A computer with an internet connection is required. I will not be diving deep into the requirements for different Operating Systems. As and when I do document loading the database on into a machine it will be RHEL8 and also I would like to document how to load the database into a container.


### Installation

*_Pending till further notice_*


<!-- MODULE1 -->
## Module 1

Basic introduction of SQL. It stands for Structured Query Language. In this module you will learn the basics of SQL. You already have learnt what the acronym stands for.


### Introduction To SQL

So we know now what SQL stands for, but what does it do ?? SQL lets you access and manipulate entries in databases. A database is simply put a collection of data. SQL can help you retrieve data, insert data, run queries,create tables, create databases and much more. We will be going over some of the most important abilities below as we progress.

*_SQL IS A STANDARD BUT_*

SQL became a standard of the American National Institute in 1982 and of the International Standard Organization in 1987 _but_ there are different versions of it. However, in order to be compliant to the ANSI and ISO standards they support at least the major commands such as 

- SELECT

- UPDATE 

- DELETE

- INSERT 

- WHERE

and some more.

*RDBMS* 

Relational Database Management System. Now if I am not mistaken, I think it was Oracle that started this concept. Earlier there were databases but they did not talk to each other. It was at Oracle that they devised a way in which these databases could communicate with each other. I could be wrong but I think I am right. Do create a pull request if you think this information can be updated.

RDBMS is the stepping stone for SQL and for all modern databases such as Oracle, IBM DB2, MS SQL Server, POSTGRES.

The data in RDBMS is stored in database objects called tables. A table is a collection of data entries and it consists of rows and columns. Rows are horizontal lines that contain data and Columns are vertical lines that hold data. A record is also called a row and a field is also known as a column.


### Syntax

- Database Tables

Each Database consists of different tables. Each table is given a name for Example Customers, Orders etc. Each table consists of different rows and columns.


- SQL Statements

Most actions that need to be performed on databases are done with SQL Statements. The below statement will select all records from the "Customers" table.

		SELECT * FROM Customers;

SQL is not case sensitive. SELECT is the same as select.

Semicolons are used to differentiate multiple SQL statements.

*FREQUENT SQL COMMANDS*

- SELECT: Extracts data from the database

- UPDATE: Updates data in the database

- DELETE: Deletes data from a database

- INSERT INTO: Inserts new data into a database

- CREATE DATABASE: Creates a new database

- ALTER DATABASE: Modifies a database

- CREATE TABLE: Creates a table in a database

- ALTER TABLE: Modifies a table

- DROP TABLE: Deletes a table

- CREATE INDEX: Creates an index (search key)

- DROP INDEX: Deletes an index
 


### Select

Extracting data is the first step and is an important step in databasae management. We need to use the *SELECT* statement to extract data. 

The syntax for a simple Select statement is:

		SELECT coulmn1,column2,...coulmn_N
		FROM TABLE_NAME;

Here column1, coulmn2 are the field names of the table you want to select data from. If you want to select all data from the table, then the syntax will be:

		SELECT * FROM TABLE_NAME;



### Select Distinct

At times there can be data that is duplicate in nature i.e it is repeated in the table for example, it could be the name of a country or name of a city. If that is the case and
we need only the unique ( distinct ) values we need to append the word *distinct* to select. It is done like so

		SELECT DISTINCT Column1 FROM TABLE_NAME;

The above statement will list only the unique values from Column1. Let's have a look at the same statement for a column with Countries in it. 

		SELECT DISTINCT Countries FROM Customers;

This will list the unique countries that Customers are from in the table called Customers.


What might be helpful is getting the count of the unique values. That can be achieved by the below statement. 

		SELECT COUNT(DISTINCT Country) FROM Customers;

COUNT is a function and we will touch base on that a little later. Right now you can try out this example on your machine. 


  
<!-- MODULE2 -->
## Module 2

Diving a little deeper into SQL with filtering and sorting of results.


### WHERE Clause

WHERE clause is used to filter the results. As the name suggests it will help us filter the results where our conditions are met. For example if we want names of Customers only from a certain Country or a City we could write a statement like this

		SELECT * FROM Customer
		WHERE Country='Denmark';

The above statement shoudl give you an idea of the syntax. It goes like this:

		SELECT Col_1,Col_2,...Col_N
		FROM TABLE_NAME
		WHERE Condition;

The WHERE clause is used not only with SELECT statement but also with other statements such as UPDATE,DELETE and many other... you will see soon enough. 

*Also please keep in mind that when using the WHERE clause if the condition is in text you need to use ' ' quotes. If the condition is in digita no quotes are required.*



### Operators in the WHERE Clause

You saw the operator = being used earlier in the WHERE clause. There are other operators as well that can be used. Some of them are listed below for your reference.

\> :Greater Than

\< :Less Than 

\>= :Greater Than or Equal To 

\<= :Less Than or Equal To

\<\> :Not Equal ( In some SQL Versions != is used for Not Equal )

LIKE :This operator searches for a pattern. We will look at this in detail a little later

BETWEEN :As the name suggests, between a certiain range.We will look at this in detail a little later

IN :To specify multiple possible values for a column. We will look at this in detail a little later





### AND OR NOT

Along with the above mentioned operators the WHERE clause can also be used with the operators "AND" "OR" "NOT".

*AND*: Displays a record if *ALL* the conditions separated by AND are true.


Usage: 

		SELECT * FROM Customers
		WHERE Country='Germany' AND City='Berlin';



*OR*: Displays a record if *ANY* of the conditions separated by OR are true.


Usage:

		SELECT * FROM Customers
		WHERE Country='Germany' OR Country='Austria';



*NOT*: Displays a record if the condition is NOT true. 


Usage:

		SELECT * FROM Customers
		WHERE NOT Country='Canada';



#### Combining AND OR NOT


Sometimes there can be a need to combine these various operators to finetune our results. What if we wanted the list of customers from Germany but only those that are from either Berlin or Munich ? We need to use parenthesis to do that. 


		SELECT * FROM Customers
		WHERE Country='Germany' AND (City='Berlin' OR City='Munic');


Another example is of combining AND and NOT

		SELECT * FROM Customers
		WHERE NOT Country='Germany' AND NOT Country='Canada';




### ORDER BY 

Often it helps if the results from a query can be sorted in a particular manner. Sorting in SQL is done by using ODER BY.
By default the query in SQL is sorted in an ASCENDING order. That is small to big. 
Should you need to specify that the result be in DESCENDING order you must write DESC at the end of the statement. 

A small example:

		SELECT * Customers
		ORDER BY Country;

Another example where we ORDER BY more than one column

		SELECT * Customers
		ORDER BY Country, CustomerName;

The same example but with DESC

		SELECT * Customers
		ORDER BY Country, CustomerName DESC;






<!-- MODULE3 -->
## Module 3

Diving still deeper into SQL with managing data in tables with insertion, deletion and updating.


### Insert Into Statement

If you need to insert data into a table you need to use the INSERT INTO statement. 

Simple syntax for the same goes something like this 

		INSERT INTO TABLE_NAME (Col_1,Col_2..Col_N)
		VALUES (Value_for_Col_1,Value_for_Col_2,Value_for_Col_N);

If you are adding values to ALL columns of the table you do not need to specify the column names BUT ensure that the values are in the same order as the columns.

		INSERT INTO TABLE_NAME
		VALUES (Value_for_Col_1,Value_for_Col_2,Value_for_Col_N);



### Null Values

A field with a NULL value is a field with no value. NULL value is different from a field with zero in it or with spaces. 
NULL value is a field that is left blank at the time of creation. For example a field which is optional.


#### Testing for NULL Values

To test for fields with NULL values we need to use the IS NULL or NOT NULL operators.

Syntax IS NULL:

		SELECT Column_name
		FROM TABLE_NAME
		WHERE Column_name IS NULL;	

Syntax NOT NULL:

		SELECT Column_name
		FROM TABLE_NAME
		WHERE Column_name IS NULL;	

_Always use IS NULL to look for NULL Values_


### Update Statement

The update statement is used to modify data in existing records of tables. 
*IMP* It should be used with a condition such as WHERE clause else all records of the table will be updated.

Syntax:

		UPDATE TABLE_NAME
		SET Col_1=value1, Col_2=value2,..Col_N=valueN
		WHERE condition;

_Remember that if the value is in text you must use quotes._



### Delete Statement

The delete statement is used to deleted existing records in a table.
*IMP* It should be used with a condition such as WHERE clause else all records of the table will be updated.


Syntax:

		DELETE FROM TABLE_NAME
		WHERE condition;

To delete all records from a table without deleting the table you can use the below statement. This means that the table structre, attributes and index will remain intact.

		DELETE FROM TABLE_NAME;






<!-- Module4  -->

## Module 4

We will learn a little about Methods a little bit about Functions and some more operators to make our life a little easier while going through data.




### Top Or Limit Or RowNum

The `SELECT TOP` clause is used to specify the number of records to return. It is useful on large tables with thousands of records.

The syntax for this is

		SELECT TOP number|percent column_name(s)
		FROM TABLE_NAME
		WHERE condition;

Example

		SELECT TOP 3 * 
		FROM Customers
		Where Country='Germany';

*Please note that not all databses accept SELECT TOP*

For MYSQL `LIMIT` is used and the above example will look something like this

		SELECT * FROM Customers
		Where Country='Germany'
		LIMIT 3;

For ORACLE as well there will be a difference since they use `ROW NUM`

		SELECT * FROM Customers
		Where Country='Germany' AND ROWNUM <= 3;


### Basic Functions

Functions in SQL are basically methods of getting results such as Count, Sum, Max, Min etc. Below are some basic functions along with their syntax for your reference. 


#### MIN\(\) MAX\(\)

As the name suggests these functions will return the minimum or maximum value from a column. 
Below is the syntax for the same

		SELECT MIN(col_name)
		FROM TABLE_NAME
		WHERE Condition;


		SELECT MAX(col_name)
		FROM TABLE_NAME
		WHERE Condition;

The brackets within which the column name is mentioned are important and part of the syntax.


#### COUNT\(\) AVG\(\) SUM\(\)

Again as the name suggests these functions provide the count, average and sum values of the records. An example for each for you to understand the syntax


		SELECT COUNT(CustomerID)
		FROM Customers;


		SELECT AVG(Price)
		FROM Products;


		SELECT SUM(Quantity)
		FROM OrderDetails;



*NOTE:NULL VALUES ARE IGNORED*

### Like Operator

The `Like` operator is used with the `WHERE` clause to search for a particular pattern in a column. A pattern is formed by using wildcards. The most common wildcards that are used with the `Like` operator are *%* and *_* The % sign represents zero,one or multiple characters. The _ represents a single character.

MSAccess uses an asterisk instead of the percent sign and a question mark in place of the underscore.

The percent sign and underscore can be used in combinations. We can also combine any number of conditions with the `AND` and `OR` operators.

Syntax for the `Like` operator is

		SELECT col_1,col_2...col_n
		FROM TABLE_NAME
		WHERE Column LIKE pattern;

Example 

		SELECT *	
		FROM Customers
		WHERE CustomerName LIKE 'a%';

This example will return all records where  CustomerNames  begins with the letter a.

We can also use the `Like` operator with the `NOT` operator to use negative conditions or to eliminate options.

		SELECT *
		FROM Customers
		WHERE Country NOT LIKE 'g%';

This example will return all records where the country's name does not begin with g.






### Wildcards

A wildcard character is used to substitute one or more characters in a string. You already have gotten a small brief above. When used with the `WHERE` clause we can search for a 
specified pattern in a column. 

Some commonly used wildcard characters in SQL are:

 \[\] represents any single character within the brackets. h\[oa\]t  will search for hot and hat.

 ^ represents any character not within the brackets. h\[^oa\]t will search for all combinations except hot and hat.

 \- represents a range of characters. h\[a-d\]t will search for hat hbt hct hdt.


All wildcard characters can be used in combinations as well. 



_PS: If you are familiar with bash, using wildcards in SQL is like globbing and regular expression._


### In Operator

The `IN` operator allows you to specify multiple values in the `WHERE` clause. You can also use the `NOT` operator with it.

Simple Syntax:

		SELECT column_name(s)
		FROM TABLE_NAME
		WHERE column_name IN (value1, value2...);

Example:

		SELECT * FROM Customers
		WHERE Country IN ( 'Germany', 'Canada');


Slightly Advanced Syntax:

		SELECT column_name(s)
		FROM TABLE_NAME
		WHERE column_name IN ( SELECT STATEMENT);

Example:

		SELECT * FROM Customers
		WHERE Country IN ( SELECT Country FROM Suppliers);

The above exaample will select all customers that are from the same countries as the suppliers.






### Between Operator

The `BETWEEN` operator will select values within a given range. The values can be numbers,text or date.

The `BETWEEN` operator is inclusive that means it will include the start and end values. Once again the `NOT` operator can be used in combination.

Syntax:

		SELECT column_name(s)
		FROM TABLE_NAME
		WHERE column_name BETWEEN value1 AND value2;

Example:

		SELECT * FROM Products
		WHERE Price BETWEEN 10 AND 20;

With `NOT`

		SELECT * FROM Products
		WHERE Price NOT BETWEEN 10 AND 20;

With `IN`

		SELECT * FROM Products
		WHERE Price BETWEEN 10 AND 20
		AND Category IN('Spices', 'Oils');

Use with Dates

		SELECT * FROM Orders
		WHERE OrderDate BETWEEN '20201-08-25' AND '2020-09-25';




### Aliases

Aliases are used to give a table or a column name a temporary name. Aliases can be useful when

- More than one table is used for a query
- Functions are used in the query
- Column names are very big and not readable
- Two or more columns are combined


Column Syntax:

		SELECT column_name AS alias_name
		FROM TABLE_NAME;

Table Syntax:

		SELECT column_name(s)
		FROM TABLE_NAME AS alias_name;

If the alias name contains a space it will need to be quoted. 


Creating one alias for multiple columns is also possible.

As an exmaple we will create an alias called "Address" which combines four columns

SQL

		SELECT CustomerName, Address + ', ' + PostalCode + ' ' + City + ', ' + Country AS Address
		FROM Customers;

MYSQL

		SELECT Addrss, CONCAT(Address,', ',PostalCode,', ',City,', ',Country) AS Address
		FROM Customers;




<!-- Module 5 -->

## Module 5


Diving deeper into the rabbit hole !! We are going to learn how to use common column(s)  to combine different tables. If you remember venn diagrams this will be a breeze.



### Joins


The `JOIN` operator is used to combine rows from two or more tables based on a column which is common in both the tables. 

We can use this functionality to match different data points to get better insights. 

Like for example in this current databasae there are two tables. Customers and Orders. 

There is a column that is common in both of them which is CutomerID. 

Using `JOIN` operators we can create a statement which will give us the number of orders for each customer.




### Inner Join


The `INNER JOIN` keyword selects records that have matching values in both the tables.


Syntax:

		SELECT column_name(s)
		FROM TABLE_1
		INNER JOIN TABLE_2
		ON TABLE_1.column_name = TABLE_2.column_name;


The `INNER JOIN` selects all rows from both tables as long as there is a match between the columns. If there are records in the "Orders" table that DO NOT have a match in "Customers" then those records will not be shown.


Example: 

		SELECT Orders.OrderID, Customers.CustomerName
		FROM Orders
		INNER JOIN Customers ON Customers.CustomerID = Customers.CustomerID;


We can use `INNER JOIN` to join three tables as well if there are columns that match.

Example: 

		SELECT Orders.OrderID, Customers.CustomerName, Shippers.ShipperName
		FROM (( Orders
		INNER JOIN Customers ON Orders.CustomerID = Customers.CustomerID)
		INNER JOIN Shippers ON Orders.ShipperID = Shippers.ShipperID);



### Left Join


The `LEFT JOIN` returns all records from the left table i.e TABLE 1 and the matched records from the right table i.e TABLE 2. The result is NULL from the right side, if there is no match. It will still return all records from TABLE 1.


Syntax:

		SELECT column_name(s)
		FROM TABLE_1
		LEFT JOIN TABLE_2
		ON TABLE_1.column_name = TABLE_2.column_name;

In some databases `LEFT JOIN` is also called as `LEFT OUTER JOIN`


Example:

		SELECT Customers.CustomerName, Orders.OrderID
		FROM Customers
		LEFT JOIN Orders
		ON Customers.CustomerID = Orders.CustomerID
		ORDER BY Customers.CustomerName;

In the above example we have displayed all the orders made by the customers. 



### Right Join


The `RIGHT JOIN` returns all records from the right table i.e TABLE 2 and the matched records from the left table i.e TABLE 1. The result is NULL from the left side, if there is no match. It will still return all records from TABLE 2. Basically the complete opposite of `LEFT JOIN`


Syntax:

		SELECT column_name(s)
		FROM TABLE_1
		RIGHT JOIN TABLE_2
		ON TABLE_1.column_name = TABLE_2.column_name;

In some databases `RIGHT JOIN` is also called as `RIGHT OUTER JOIN`


Example:

		SELECT Orders.OrderID, Employees.LastName, Employees.FirstName
		FROM Orders
		RIGHT JOIN Employees ON Orders.EmployeeID = Employees.EmployeeID
		ORDER BY Orders.OrderID;	

In the above example we will be dsiplayed all employess and any orders that they might have placed.

The `RIGHT JOIN` will return all records from the right table i.e Employees even if there are no matches on the left table i.e Orders.




### Full Outer Join


The `FULL OUTER JOIN` will return all records when there is a match in left i.e TABLE 1 or right i.e TABLE 2 records. This operator can return very large data sets.

In some databases `FULL OUTER JOIN` is called as `FULL JOIN`


Syntax:

		SELECT column_name(s)
		FROM TABLE_1
		FULL OUTER JOIN TABLE_2
		ON TABLE_1.column_name = TABLE_2.column_name
		WHERE condition;


Example:

		SELECT Customers.CustomerID, Orders.OrderID
		FROM Customers
		FULL OUTER JOIN Orders
		ON Customers.CustomerID = Orders.CustomerID
		ORDER BY Customers.CustomerName;

In the above example we will be displayed all orders of all customers. If a customer does not have an order a NULL value will be displayed but the record will be shown.
		



### Self Join

A `SELF JOIN` is a regular join where in the table is joined with itself. Alias is used to further divide the columns which will then later get matched.


Syntax:

		SELECT column_name(s)
		FROM TABLE_1 AS t1, TABLE_2 As t2
		WHERE condition;

Let us try this from the "Customers" table where in we want to find out all the customers with the same city.

		SELECT A.CustomerName AS CumstomerName1, B.CustomerName AS CustomerName2, A.City
		FROM Customers A, Customers B
		WHERE CustomerName1 <> CustomerName2
		AND A.City = B.City
		ORDER BY A.City;




### Union Operator


The `UNION` operator is used to combine the result-set of two `SELECT` statements.

- Each `SELECT` statement within the `UNION` operator should have the same number of columns.

- The column must have similar data types

- The columns in each `SELECT` statement must also be in the same order.

When we use `UNION` operator duplicate values will not be displayed. For that we need to use the `UNION ALL` operator


Syntax `UNION`

		SELECT column_name FROM TABLE_1
		UNION
		SELECT column_name FROM TABLE_2;

Syntax `UNION ALL`

		SELECT column_name FROM TABLE_1
		UNION ALL
		SELECT column_name FROM TABLE_2;


The column names in the result-set are usually equal to the column names in the first `SELECT` statement in the union.


Example:

		SELECT City FROM Customers
		UNION
		SELECT City FROM Suppliers
		ORDER BY City;

The above example will return us a data-set of a list of cities which have Customers and Suppliers. It will display only distinct values. For all values even those that are being repeated usel `UNION ALL`.


`UNION` with `WHERE`

		SELECT City,Country FROM Customers
		WHERE Country = 'Germany'
		UNION 
		SELECT City,Country FROM Suppliers
		WHERE Country = 'Germany'
		ORDER BY City;

Again in the above example only distinct cities will be displayed from Germany. Use `UNION ALL` for repetitve values.


<!-- Module 6 -->

## Module 6


### Group By Statement

### Having Clause	

### Exists Operators

### ANY and ALL Operators

### Select Into Statement

### Insert Into Select Statement

### Case Statement

### Null Functions

<!-- Module 7 -->
### Module 7

### Stored Procedure

### Comments

### Operators
	

<!-- Module 8 -->

## Module 8

### Create Database

### Drop Database

### Backup Database

### Create Table

### Alter Table

### Constraints

### Not Null Constraints

### Unique Constraints

### Primary Key Constraint

### Foreign Key Constraint

### Check Constraint

### Default Constraint

### Create Index Statement

### Auto Increment Field

### Working With Dates

### Views

### Injection

### Hosting

### Data Types
	<
<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

Your Name - [@your_twitter](https://twitter.com/your_username) - email@example.com

Project Link: [https://github.com/your_username/repo_name](https://github.com/your_username/repo_name)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [GitHub Emoji Cheat Sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [GitHub Pages](https://pages.github.com)
* [Animate.css](https://daneden.github.io/animate.css)
* [Loaders.css](https://connoratherton.com/loaders)
* [Slick Carousel](https://kenwheeler.github.io/slick)
* [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
* [Sticky Kit](http://leafo.net/sticky-kit)
* [JVectorMap](http://jvectormap.com)
* [Font Awesome](https://fontawesome.com)





<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/doctypehuman/Best-README-Template.svg?style=for-the-badge
[contributors-url]: https://github.com/doctypehuman/sql/contributors
[forks-shield]: https://img.shields.io/github/forks/doctypehuman/Best-README-Template.svg?style=for-the-badge
[forks-url]: https://github.com/doctypehuman/sql/network/members
[stars-shield]: https://img.shields.io/github/stars/doctypehuman/Best-README-Template.svg?style=for-the-badge
[stars-url]: https://github.com/doctypehuman/sql/stargazers
[issues-shield]: https://img.shields.io/github/issues/doctypehuman/Best-README-Template.svg?style=for-the-badge
[issues-url]: https://github.com/doctypehuman/sql/issues
[license-shield]: https://img.shields.io/github/license/doctypehuman/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/doctypehuman/sql/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/
roduct-screenshot]: images/screenshot.png
