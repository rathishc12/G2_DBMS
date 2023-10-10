# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 

create table student1(rollno int,name char(20),age int,addr varchar(20),phoneno int);

### OUTPUT:
![273106868-8c30bf4f-04a8-4969-8bab-b0a731fcf67d](https://github.com/rathishc12/G2_DBMS/assets/120539398/3c10c896-71a1-44eb-a229-543b1bcfb194)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student1 add department char(30);
### OUTPUT:
![273106972-8c46886c-34f0-4c28-8a89-09b10bf3a545](https://github.com/rathishc12/G2_DBMS/assets/120539398/a7717f96-5e88-4687-a2a2-86dad494c239)


### 3) Drop the student table
### SQL QUERY: 
drop table student2;
### OUTPUT:
![image](https://github.com/rathishc12/G2_DBMS/assets/120539398/4a1b4c4d-f5ae-4c61-b5b1-9db0d234adf6)


### 4) Delete the student table using truncate keyword
### SQL QUERY: 
truncate table student1;
### OUTPUT:
![273107088-5f60da4d-0f7a-4056-9321-a9a53b56635f](https://github.com/rathishc12/G2_DBMS/assets/120539398/2917d7dd-13b8-4a44-9561-d2bf09207b49)


### 5) Rename the student table to mystudent
### SQL QUERY: 
alter table student rename to mystudent2;
### OUTPUT:
![273107335-c9836478-e202-401e-8f14-fd1c4eaba589](https://github.com/rathishc12/G2_DBMS/assets/120539398/9a5e364a-f0ab-4227-9f62-7a45ad85be39)

