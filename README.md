# school_details_proj

## Requirements
1. This project was made in NetBeans 8.2 ```(may not be compatible with newer versions)```
2. [MySQL version: 8.0.28](https://dev.mysql.com/downloads/file/?id=510039) ```(is not compatible with older versions)```
3. [MySQL java connector version: 8.0.28](https://dev.mysql.com/downloads/file/?id=509728) required. ```(is not compatible with older versions)```

## Usage Instruction
1. Clone this repository
2. [Make database in MySQL](#instructions-to-make-the-mysql-database)
3. Import project into NetBeans
4. Edit in your MySQL login id (usually ```root```) and password in the [whole code](#where-to-make-changes-in-files).
4. Run project from file : School_details_code.java

## Instructions to make the MySQL database
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

## Where to make changes in files
1. ```admin_login.java  : line 125```
2. ```frame1.java       : line 47 & 195```
3. ```frame2.java       : line 142```
4. ```frame3.java       : line 217```
5. ```frame4.java       : line 44```
6. ```marks.java        : line 154```