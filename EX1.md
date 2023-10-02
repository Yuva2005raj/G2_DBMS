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
```
create table student(rollno int,name char(20),age int,address varchar(20),phoneno int);
```

### OUTPUT:

![271202265-0ef4f197-c7f6-457f-9c14-99ff64c8e0ea](https://github.com/Yuva2005raj/G2_DBMS/assets/118343998/95acdc13-410a-4378-8738-9f0e43da936b)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:

![271202634-9da807a2-282a-48db-9eac-c2b8998d3403](https://github.com/Yuva2005raj/G2_DBMS/assets/118343998/b169044f-8dfe-4151-b9c4-e07c880c5fec)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;
```

### OUTPUT:

![271203708-2d2245a9-b680-4a82-867f-3b37164ddd6f](https://github.com/Yuva2005raj/G2_DBMS/assets/118343998/8d9f805c-9a4b-4c8d-8dcf-e19494704586)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
```
truncate table student;
```

### OUTPUT:

![271203782-490d77b7-d304-47af-b312-72c8967d392a](https://github.com/Yuva2005raj/G2_DBMS/assets/118343998/9c908812-33d0-4d2e-a3dc-bcdca2e767b3)



### 5) Rename the student table to mystudent

### SQL QUERY: 
```
alter table student rename to mystudent;
```

### OUTPUT:

![271204102-8e2a54e9-316c-4ad4-955a-db9ba7aec8c0](https://github.com/Yuva2005raj/G2_DBMS/assets/118343998/a7140f4a-6a11-4bfc-84f2-81250d7664d6)

## RESULT:
To create a student database and execute DDL queries using SQL is executed successfully.
