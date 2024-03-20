# EXP NO 2: DATA DEFINITION LANGUGE COMMANDS 
### DATE
## AIM:
To create a student database and execute DDL queries using SQL.


## THEORY
### DDL (Data Definition Language)

* DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema.
* It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database.
* DDL is a set of SQL commands used to create, modify, and delete database structures but not data.
* These commands are normally not used by a general user, who should be accessing the database via an application.

 
### List of DDL commands: 
1. CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
2. DROP: This command is used to delete objects from the database.
3. ALTER: This is used to alter the structure of the database.
4. TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
5. RENAME: This is used to rename an object existing in the database.

## Query:

## 1) Create a table student and insert any two rows with the following fieds RegisterNumber,Name,Age,Address,Phone number

## SQL QUERY:
```
create table students(
    registernumber integer,
    name varchar(50),
    age integer,
    address varchar(60),
    phonenumber integer
    
);
``` 
## OUTPUT:

![312322071-28576b8f-dc1a-4950-aa2d-efa3a0c0adc5](https://github.com/Yazhini-G/DBMS/assets/120244201/399cce5a-9317-444b-97be-6d3a4ef4a418)

## 2) Alter the above student table by adding another attribute department
## SQL QUERY:
```
alter table students
add department char(80);
 ```
## OUTPUT:

![312324660-79e91054-1c31-40ad-a62f-44590f1f595b](https://github.com/Yazhini-G/DBMS/assets/120244201/2dba4cb6-8a85-4a46-95a4-3acafcc33eaf)

## 3) Rename the student table to mystudent
## SQL QUERY:
```
alter table students rename to mystudent;

```
## OUTPUT:

![312325386-a26a4b95-77f2-458c-a9d0-338e2649c32d](https://github.com/Yazhini-G/DBMS/assets/120244201/6e458657-0feb-4b13-af70-9bccb08ed010)

## 4) Delete the mystudent rows using truncate keyword
## SQL QUERY:
```
truncate table students
```
## OUTPUT:

![312327472-817ce03a-f376-4cce-ae60-dbb906eaadba](https://github.com/Yazhini-G/DBMS/assets/120244201/2b3de822-3685-4775-aa7a-848d9c832dcc)

## 5) Drop the mystudent table
## SQL QUERY:
```
drop table students;
```
## OUTPUT:

![312326420-54dcf9fb-3137-4e6a-8119-d005c29705b6](https://github.com/Yazhini-G/DBMS/assets/120244201/0e66c61b-3159-442b-aff3-311a4ce0df73)

## Result:
Thus the basic DDL commands in SQL are executed. 


