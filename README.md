# school_details_proj

## Instructions
1. This project was made in NetBeans 8.2
2. MySQL version : 8.0.28
3. MySQL java connector version 8.0.28 required.

## Usage Instruction
1. Clone this repository
2. Make database in MySQL
3. Import project into NetBeans
4. Make changes to sql login id and password in the whole code.
4. Run project from file : School_details_code.java

## Instructions to make SQL databases
```
CREATE DATABASE student_details;
```
```
USE student_details;
```
```
CREATE TABLE student_details(sr_no INT NOT NULL AUTO_INCREMENT, stu_name varchar(40), fat_name varchar(40), mot_name varchar(40), course varchar(40), grade varchar(2), primary key (sr_no));
```
```
CREATE TABLE login_details(sr_no INT NOT NULL AUTO_INCREMENT, user_name varchar(40), user_pass varchar(40), primary key (sr_no));
```
```
CREATE TABLE admin_login(admin_name varchar(40), admin_pass varchar(40));
```
```
CREATE TABLE student_marks(sr_no INT NOT NULL AUTO_INCREMENT, paper1 varchar(3), paper2 varchar(3), paper3 varchar(3), paper4 varchar(3), primary key (sr_no));
```