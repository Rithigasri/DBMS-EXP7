# EXPERIMENT 07:AGGREGATE FUNCTION IN SQL
## AIM:
To perform aggregation functions in SQL.

## ALGORITHM:
1. Create a table and insert values using keywords "create table","insert into values". 
2. Display the table using "select" 
3. Using sum() , count() and avg() perform the operations. 
4. Display the result.

## PROGRAM:
```
-- create
CREATE TABLE STUDENT (
  sid INTEGER PRIMARY KEY,
  sname TEXT NOT NULL,
  smark TEXT NOT NULL
);

-- insert
INSERT INTO STUDENT VALUES (0001, 'Clark',83);
INSERT INTO STUDENT VALUES (0002, 'Dave',67);
INSERT INTO STUDENT VALUES (0003, 'Ava', 92);
INSERT INTO STUDENT VALUES (0004, 'Tom', 78);
INSERT INTO STUDENT VALUES (0005, 'Ava', 59);

-- fetch 
SELECT * FROM STUDENT ;

SELECT SUM(smark) "SUM : " FROM STUDENT;
SELECT count(*) "Count : "FROM STUDENT;
SELECT avg(smark) "Average : "FROM STUDENT;
```
## OUTPUT :
![image](https://github.com/Rithigasri/DBMS-EXP7/assets/93427256/9c2cc863-c38e-40a3-8d37-33b51654009e)
![image](https://github.com/Rithigasri/DBMS-EXP7/assets/93427256/c61d0a27-0ba7-4134-9cbf-f03c3d19078f)

## RESULT :
Hence, the aggregation functions in SQL are performed successfully.
