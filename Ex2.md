# EX 2 Data Manipulation Language (DML) Commands and built in functions in SQL
## AIM:
To create a manager database and execute DML queries using SQL.


## DML(Data Manipulation Language)
<div align="justify">
The SQL commands that deal with the manipulation of data present in the database belong to DML or Data Manipulation Language and this includes most of the SQL statements. It is the component of the SQL statement that controls access to data and to the database. Basically, DCL statements are grouped with DML statements.
</div>

## List of DML commands: 
<div align="justify">
INSERT: It is used to insert data into a table.<br>
UPDATE: It is used to update existing data within a table.<br>
DELETE: It is used to delete records from a database table.<br>
</div>

## Create the table as given below:
```sql
create table manager(enumber number(6),ename char(15),salary number(5),commission number(4),annualsalary number(7),Hiredate date,designation char(10),deptno number(2),reporting char(10));
```
## insert the following values into the table
```sql
insert into manager values(7369,'Dharani',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Sobbo',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhithiya',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikashark',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/150d7797-c398-4a75-b7d1-b731bac9a563)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/b1c6ce00-d597-4430-b5f0-7d7884371ab1)



### Q2) Delete the records from manager table where the salary less than 2750.
## QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/46fb3fbd-c9e2-4911-b43c-e1574d183e37)


## OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/3c4e6c69-35b7-4cda-a2f3-e0e648f81272)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)
### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/78be90ee-8707-45f4-9dfe-385b916f3bb0)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/5145671b-c03a-4089-8bca-1c3b60c3bcd3)



### Q5)	List the names of Clerks from emp table.
## QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/be937ee1-2f29-4603-bd92-3651c0a7f809)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/78785bfb-500b-4eea-ba49-0afb1de5854d)



### Q6)	List the names of employee who are not Managers.
### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/ad6dbcf3-5d68-47bf-853b-6033c7518fd9)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/bc8db5d5-5ef5-4e24-b67d-aa8d05384e98)


### Q7)	List the names of employees not eligible for commission.
### QUERY:
 ![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/52ea2b34-5f76-4b25-bfd2-19445508eb34)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/ca5eb987-0b62-437a-8d1c-73b6b9307939)




### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/a1875b08-a5a3-45a9-81df-ea1bea66dfc9)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/4903b3da-b8bc-431c-ad73-f04ad7d790fb)




### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/67c73c8d-9c2f-4f22-bc81-f9506a079afa)




### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/3fdf40c6-c8d2-4b0c-a689-058ab9ed6e92)




### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/1eb95e22-459b-4c4a-bfd4-061c4ffcc028)




### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/ef540435-a1be-47b1-aae8-905cf41ae40e)



### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/245e2d24-0ffb-45f6-9cd2-899f69bca2a3)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/ce6cab51-0f45-4927-ae13-d6b7c79aa1d3)




### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/f637f7fb-9e9c-45b8-a1da-dcb1e6726244)






### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/6c1f3505-736e-4510-ac0e-0311ebd9bc51)



### Q13) Find number of rows in the table EMP

### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/6afc6af9-6d2e-4372-86cc-4332e5f6a566)



### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/889ff357-c701-4da3-aae1-628931aceb04)




### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/191c4267-1e5c-4c44-9863-dfbc798104a5)




### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/cf64be87-1032-441a-bbfa-5e61e8100826)




### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/20066b02-938b-435b-bd5d-2ca760d3b79e)




### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/86da09bc-0f85-4b01-9db6-aa7d84cf651a)


### RESULT:
Thus the Data Manipulation Language (DML) Commands and built in functions in SQL
