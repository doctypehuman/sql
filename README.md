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
	<li><a href="Insert-Into-Statement">Insert Into Statement</a></li>
	<li><a href="Null-Values">Null Values</a></li>
	<li><a href="Update-Statement">Update Statement</a></li>
	<li><a href="Delete-Statement">Delete Statement</a></li>
	</ul>
    <li><a href="#Module-4">Module 4</a></li>
    <li><a href="#Module-5">Module 5</a></li>
    <li><a href="#Module-6">Module 6</a></li>
    <li><a href="#Module-7">Module 7</a></li>
    <li><a href="#Module-8">Module 8</a></li>
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
