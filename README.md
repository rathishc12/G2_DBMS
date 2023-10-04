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

create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);

### OUTPUT:

![image](https://github.com/rathishc12/G2_DBMS/assets/120539398/781b105c-459f-46cc-8d7d-db198b48de70)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
alter table student add department char(30);
### OUTPUT:

![image](https://github.com/rathishc12/G2_DBMS/assets/120539398/f2353c71-67fe-4d36-8d32-45242052d03f)


### 3) Drop the student table
 
### SQL QUERY: 
drop table student;

### OUTPUT:

![image](https://github.com/rathishc12/G2_DBMS/assets/120539398/cdfe7155-760a-48a9-a540-40f5364fdd32)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
truncate table student;

### OUTPUT:

![image](https://github.com/rathishc12/G2_DBMS/assets/120539398/af6c6bbf-1b64-4c42-8365-0d0e42db1a84)



### 5) Rename the student table to mystudent

### SQL QUERY: 
alter table student rename to mystudent;

### OUTPUT:
![image](https://github.com/rathishc12/G2_DBMS/assets/120539398/075bf3d6-31a4-4b6e-9a57-9a264f6a9c7d)

### RESULT:
hence successfully created a student database and execute DDL queries using SQL.



