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
insert into manager values(7369,'Dharsan',2500,500,30000,'30-June-81','clerk',10,'John');
insert into manager values(7839,'Subu',3000,400,36000,'1-Jul-82','manager',null,'James');
insert into manager values(7934,'Aadhi',3500,300,42000,'1-May-82','manager',30,NULL);
insert into manager values(7788,'Vikash',4000,0,48000,'12-Aug-82','clerk',50,'Bond');
```

### Q1) Update all the records of manager table by increasing 10% of their salary as bonus.

### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/20b5ab62-66de-4934-a8ae-7f666206f632)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/d5558323-bfa4-4104-ae96-2f7a984d627d)


### Q2) Delete the records from manager table where the salary less than 2750.
## QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/46fb3fbd-c9e2-4911-b43c-e1574d183e37)


## OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/3c4e6c69-35b7-4cda-a2f3-e0e648f81272)


### Q3) Display each name of the employee as “Name” and annual salary as “Annual Salary” (Note: Salary in emp table is the monthly salary)
### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/6784d296-d5ef-498d-a21e-3ffaa41389f3)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/351ecc3d-3113-4b9c-b4f1-00f20c7ad0c0)


### Q5)	List the names of Clerks from emp table.
## QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/ec04671d-d723-4f00-bccf-cd4978f960ac)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/352c29e7-33ec-4dd8-95eb-2157fb81d925)


### Q6)	List the names of employee who are not Managers.
### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/ad6dbcf3-5d68-47bf-853b-6033c7518fd9)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/bc8db5d5-5ef5-4e24-b67d-aa8d05384e98)


### Q7)	List the names of employees not eligible for commission.
### QUERY:
 ![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/4ac256c3-fda8-4935-b5c8-b49dd4cd39c2)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/bb9263a2-0400-482a-89b2-13661809f221)



### Q8)	List employees whose name either start or end with ‘s’.


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/1369f857-2077-4b9e-9f81-2a5308aeeb0b)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/49006793-3379-41ca-80cb-255d3b0e2baa)



### Q9) Sort emp table in ascending order by hire-date and list ename, job, deptno and hire-date.


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/2dea63fe-be52-47b0-8ab4-3cfc53aca8cd)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/bc11524a-2b5b-4cc5-97af-525d4cf91482)



### Q10) List the Details of Employees who have joined before 30 Sept 81.


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/a420fbed-5762-4f6f-8cfa-e106be8fe0c3)



### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/da07326c-27a8-48c7-9530-1d8f41780b78)



### Q11)	List ename, deptno and sal after sorting emp table in ascending order by deptno and then descending order by sal.


### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/0a218316-cc87-4f9b-b5fc-36d017655f76)


### OUTPUT:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/3bda7895-6c27-4da6-871c-1e14f5c205a9)



### Q12) List the names of employees not belonging to dept no 30,40 & 10


### QUERY:
![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/29fd74c8-fb4f-4db0-9505-78767ff8c0bd)



### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/79f8f49b-c25c-4b4f-91aa-5a1f298d4c89)


### Q13) Find number of rows in the table EMP

### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/cf10893e-baea-46f8-8fba-a5dcfb09ca51)


### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/db62fdc9-5306-40cb-b50f-ec495a29931c)



### Q14) Find maximum, minimum and average salary in EMP table.

### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/29e90f98-773c-48f0-91b2-691805bcc51c)



### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/bf994717-9c39-46d3-89ea-5c24a77182c5)



### Q15) List the jobs and number of employees in each job. The result should be in the descending order of the number of employees.

### QUERY:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/2052818f-1beb-48bf-8ec3-c031c3d84777)



### OUTPUT:

![image](https://github.com/JivanKarthick/EX-2-Data-Manipulation-Language-DML-and-Data-Control-Language-DCL-Commands/assets/121165867/1f9af77c-0b9e-4d6d-b607-eec83210ff11)

### RESULT:
Thus the Data Manipulation Language (DML) Commands and built in functions in SQL
