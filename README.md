# Ex-07-Aggregate-function-in-SQL
## AIM:-
To write a sql query to perform Aggregate function in SQL.

## PROCEDURE:-
### STEP 1:
create database AGGREGATE_FUNCTION.

### STEP 2:
create table DETAILS with ID and value.

### STEP 3:
Insert Value to the table DETAILS.

### STEP 4:
Perform Aggregate functions like SUM(),COUNT(),AVG().

## PROGRAM:-
```sql
CREATE DATABASE AGGREGATE_FUNCTION;
USE AGGREGATE_FUNCTION;
CREATE TABLE DETAILS (
  ID INT PRIMARY KEY,
  Value INT
);
INSERT INTO DETAILS (ID, Value) VALUES
(1, 10),
(2, 20),
(3, 30),
(4, 40),
(5, 50);
SELECT * FROM DETAILS;
SELECT SUM(Value) FROM DETAILS;
SELECT COUNT(*) FROM DETAILS;
SELECT AVG(Value) FROM DETAILS;
```
## OUTPUT:-
![image](https://github.com/Kirupanandhan/Exp-7-Aggregate-function-in-SQL/assets/94386222/9ccbb7a7-9edd-4d66-ba2e-212855aa9c93)

![image](https://github.com/Kirupanandhan/Exp-7-Aggregate-function-in-SQL/assets/94386222/ef237690-21a8-4d6f-855f-4bc52d5ad583)

![image](https://github.com/Kirupanandhan/Exp-7-Aggregate-function-in-SQL/assets/94386222/b4095035-7619-458f-ac7a-c12b27affd31)

![image](https://github.com/Kirupanandhan/Exp-7-Aggregate-function-in-SQL/assets/94386222/036033e2-cd27-42ad-a560-9e9a259f01ab)
## RESULT:-
A sql query to perform Aggregate function in SQL has been executed.
