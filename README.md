# student-management-system
Student management system project in python

****Requirements and Installation****

Use pip3 instead of pip for Linux and Mac.

Install PyMySQL
☛pip install PyMySQL

Install Tkinter
☛pip install tk



****Install MySQL server****



****Create a Database and a Table****

Create a database with this name: "student_management"
☛create database student_management;

Create a table "student_register" under the "student_management" database.
☛create table student_register(
	f_name VARCHAR(50) NOT NULL,
	l_name VARCHAR(50) NOT NULL,
	course VARCHAR(30) NOT NULL,
	subject VARCHAR(50) NOT NULL,
	year Int(10) NOT NULL,
	age Int(10) NOT NULL,
	gender char(10) NOT NULL,
	birth DATE NOT NULL,
	contact VARCHAR(15) NOT NULL,
	email VARCHAR(100) NOT NULL,
	PRIMARY KEY ( contact )
);
