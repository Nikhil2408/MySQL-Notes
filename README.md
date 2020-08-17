# MySQL-Notes

This repository contains notes on MySQL which I have prepared while learning it. This repository will be updated whenever I find something new and useful related to MySQL. Learners can take full advantage of this repository. 

Let's start learning.......

<h2> What is a Database? </h2>

A database can be defined as a collection of data. It is a collection of information that is organized so that it can be easily accessed, managed and updated. The data stored in a database can be of anything either sales data, transaction data or even simple records.

If I talk about a physical database, a phonebook is an example of it. :sweat_smile:

<h2> Database Management System </h2>

The simplest definition of Database Management System is that it is a software which is used to manage(acesss, update) the database. DBMS provides an interface to perform various operations like database creation, storing data in it, updating data, creating a table in the database and a lot more.
 
Examples are:- MySQL, Oracle database, PostgreSQL and many more.

![](images/DBMS.png)

<h2> Difference between MySQL and SQL </h2>

SQL which stands for structured query language is a language which is used by the database management system to interact with the databases. All relational database management system make use of SQL to interact with the database. All relational DBMS use SQL but that does not mean that all are identical. They is a slight difference in syntax in every DBMS and also the features of database management system are different from each other.

<b> Important point to note:</b> The SQL keywords are not case-sensitive.

<b> Let's get our hands dirty on some commands :computer: </b> 

For any help just type the following command in MySQL prompt.
```bash
help;
```

To see all the databases created so far, type the following command.
```bash
show databases;
```

We can create different databases for different applications. Any number of databases can be created. To create a database use the following command.
```bash
CREATE DATABASE <database_name>;
```
You can verify the database created using the "show databases;" command which has been already told.

To use a particular database or to switch to a particular database and start working on it, use the following command.
```bash
use <database_name>;
```
To know what database is currently used by us, use
```bash
SELECT database();
```
 
To delete a database, use the following command.
```bash
DROP DATABASE <database_name>;
```

<h2> Tables </h2>
A collection of related data held in a structured format within a database.

<h2> Data Types </h2>

Here is the image that displays all the datatypes used in MySQL.

![](images/Data_Types.png)

* VARCHAR is variable length, while CHAR is fixed length. CHAR is a fixed length string data type, so any remaining space in the field is padded with blanks. CHAR takes up 1 byte per character. VARCHAR is a variable length string data type, so it holds only the characters you assign to it.

To create a table, use the following syntax:

```bash
CREATE TABLE table_name(column_name1 datatype, column_name2 datatype,.....);
```

To see the structure of the table created:-
```bash
desc <table_name>;
```


<h1> Will be continued later....</h1>








 
