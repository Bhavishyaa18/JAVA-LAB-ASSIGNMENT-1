⭐ README – Student Record Management System (Java Assignment)
Project Title

Student Record Management System – Java OOP Assignment

Introduction

This project is a simple Java-based Student Record Management System developed to demonstrate the concepts of Object-Oriented Programming (OOP) such as classes, objects, constructors, inheritance, methods, and arrays/collections.

The program allows the user to:

Add new student records

Display all stored student details

Automatically calculate grades based on marks

Features

Uses Person → Student inheritance model

Accepts user input using the Scanner class

Stores multiple student objects using ArrayList

Provides a menu-driven interface

Calculates grade automatically

Clean and easy-to-understand code

Class Structure
1. Person Class

Contains: name

2. Student Class (extends Person)

Contains: rollNo, course, marks, grade

Constructors: Default and Parameterized

Methods:

inputDetails()

calculateGrade()

displayDetails()

3. StudentRecordApp (Main Class)

Contains the main menu

Manages the ArrayList of students

Handles Add, Display, and Exit options

Grade Calculation Rules
Marks Range	Grade
90 – 100	A
75 – 89	B
60 – 74	C
Below 60	D
How to Run the Program
Step 1: Save the File

Save the code in a file named:

StudentRecordApp.java

Step 2: Open in IntelliJ / VS Code / Command Line
Step 3: Compile the program
javac StudentRecordApp.java

Step 4: Run the program
java StudentRecordApp

Sample Output
===== Student Record Menu =====
1. Add Student
2. Display All Students
3. Exit
Enter your choice: 1
Enter Roll No: 101
Enter Name: Rahul
Enter Course: B.Tech
Enter Marks: 87.0

Technologies Used

Java

OOP Concepts

ArrayList

Scanner for input

Author

BHAVISHYA SAIN
B.Tech CSE Core
Section B
