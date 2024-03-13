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
create table STUDENT(S_Roll_no int,S_Name char(20),S_Age int,S_Address char(30),S_Phone_no int);
``` 
## OUTPUT:
![278823065-546b7d10-2f3d-458c-93e1-263c178605ac](https://github.com/Yazhini-G/DBMS/assets/120244201/ad247cf0-1907-44ea-9165-cc44b868d045)

![278823566-b54338cb-c3e0-4a0a-908b-516c499aacbe](https://github.com/Yazhini-G/DBMS/assets/120244201/0f213322-8771-4daf-954c-ff3001d68255)

## 2) Alter the above student table by adding another attribute department
## SQL QUERY:
```
alter table STUDENT add S_Dept char(10);
 ```
## OUTPUT:
![278823089-7a6f43c2-7722-4ccc-9c50-187dec02d321](https://github.com/Yazhini-G/DBMS/assets/120244201/54e24e8b-e397-497f-bb80-02017fea5cca)


## 3) Rename the student table to mystudent
## SQL QUERY:
```
rename table STUDENT to MYSTUDENT;
```
## OUTPUT:
![278823228-4caaee67-1fe4-4a30-acfe-0fff0dd693ab](https://github.com/Yazhini-G/DBMS/assets/120244201/59e766f1-35e0-483b-9e7a-41ea160e1f4b)


## 4) Delete the mystudent rows using truncate keyword
## SQL QUERY:
```
truncate table STUDENT;
```
## OUTPUT:

![278823271-34efe174-772c-4be9-80f5-3b82a131252e](https://github.com/Yazhini-G/DBMS/assets/120244201/336b03a7-b8d5-48f7-9117-a81a49835d80)

## 5) Drop the mystudent table
## SQL QUERY:
```
drop table MYSTUDENT;
```
## OUTPUT:
![278823299-07813b5d-909c-424f-94fc-769b28adebfd](https://github.com/Yazhini-G/DBMS/assets/120244201/16dec598-85c1-4495-9fe7-036336e95dac)

## Result:
Thus the basic DDL commands in SQL are executed. 


