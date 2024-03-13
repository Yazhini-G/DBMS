# EXP NO 1: ER DIAGRAM CREATION, RELATIONAL MODEL AND SCHEMA GENERATION  
### DATE
## AIM:
<div align="justify">
   To create a ER Diagram for Bank management system or College management system using ERD Plus tool and generate the relational model with schema. 
</div>

## Algorithm
1. Create a login with https://erdplus.com.
2. Create a new ER Diagram with name
3. Create a strong entity, relation and attributes.
4. Create a weak entity, relation and attributes.
5. Specify attributes unique, multivalued and composite attributes.

### ER Diagram 
![University Database](https://github.com/Yazhini-G/DBMS/assets/120244201/489b3b44-a3c6-4e35-b774-26f17531f82d)
### Relational model
![College Database relational scheme](https://github.com/Yazhini-G/DBMS/assets/120244201/dc97060a-4d3b-42d5-9f40-62107a5021bc)
### SQL DDL Schema 
```
CREATE TABLE Student
(
  Student_id INT NOT NULL,
  Firstname INT NOT NULL,
  Lastname INT NOT NULL,
  Birthdate INT NOT NULL,
  Yearenrolled INT NOT NULL
);

CREATE TABLE Program
(
  Name INT NOT NULL,
  Program_id INT NOT NULL,
  Credits INT NOT NULL,
  Yearcommened INT NOT NULL,
  PRIMARY KEY (Program_id)
);

CREATE TABLE Instructor
(
  Instructor_Name INT NOT NULL,
  Instructor_ID INT NOT NULL,
  Email INT NOT NULL,
  Phone_Number INT NOT NULL
);

CREATE TABLE Enrollment_&_Course
(
  Course_name INT NOT NULL,
  Course_ID INT NOT NULL,
  Enrollment_ID INT NOT NULL,
  Student_Register_Number INT NOT NULL,
  Credits INT NOT NULL
);

CREATE TABLE Department
(
  Department_ID INT NOT NULL,
  Department_Name INT NOT NULL
);
```
## RESULT 
<div align="justify">
Thus the ER diagram was drawn and relational diagram, SQL DDL staements are generated using ERD plus tool.
</div>
