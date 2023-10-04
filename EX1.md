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
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/025d6b30-8d3f-4a44-96fd-da6c0443e9d7)

### OUTPUT:
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/edc47576-f362-462b-8fe7-453cee1e6932)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/ae56851d-96b1-4406-bb29-de4aca4d2eee)

### OUTPUT:
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/12f1d397-52ef-4d6b-a50c-f531817dc568)


### 3) Drop the student table
 
### SQL QUERY: 
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/e4c7ca9b-af7b-4dda-87d5-9219401cb8b0)

### OUTPUT:
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/35d12e9a-f712-4328-bbcd-d95fd66c3bbe)



### 4) Delete the student table using truncate keyword
### SQL QUERY: 
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/23f806dc-3648-44fd-840c-d9494292bc6a)

### OUTPUT:
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/243e054d-0cab-475b-b139-db265c35fa9e)


### 5) Rename the student table to mystudent
### SQL QUERY: 
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/9676d5b8-8271-4197-a006-3b12b2cb295c)

### OUTPUT:
![image](https://github.com/SanjithaBolisetti/G2_DBMS/assets/119393633/531666d7-be37-46ec-bdbe-1c2dcc257cd1)


### RESULT:
Creating a student database and execute DDL queries using SQL is executed successfully.
