📘 Student Management System – Java (Inheritance, Interfaces, Polymorphism)

This project implements a Student Management System in Java using advanced Object-Oriented Programming concepts such as inheritance, abstract classes, interfaces, method overloading, method overriding, and polymorphism. It provides full CRUD functionality (Add, Update, Delete, Search, View) for managing student records.

🚀 Features

Abstract class Person with shared attributes

Student class extending Person

Interface RecordActions defining CRUD methods

StudentManager implementing RecordActions

Method Overloading & Overriding

Prevents duplicate roll numbers

Stores student records using HashMap

Fully menu-driven system

Compatible with all online Java compilers

🧩 Object-Oriented Concepts Demonstrated ✔ Inheritance

Student inherits from Person.

✔ Abstract Class

Person contains an abstract method displayInfo() implemented by Student.

✔ Interface Implementation

StudentManager implements all CRUD methods from RecordActions.

✔ Method Overloading

Student.displayInfo() is overloaded with a string parameter.

✔ Method Overriding

Student.displayInfo() overrides the abstract method in Person.

✔ Polymorphism

Accessing objects using parent class / interface references.

🏗 Class Overview Person (abstract class)

name

email

abstract displayInfo()

Student (extends Person)

rollNo

course

marks

grade

overrides displayInfo()

overloaded displayInfo(String note)

RecordActions (interface)

Methods:

addStudent()

deleteStudent()

updateStudent()

searchStudent()

viewAllStudents()

StudentManager (implements RecordActions)

Stores students in HashMap<Integer, Student>

Implements all CRUD operations

Main (driver class)

Contains the main menu loop.

📦 How to Run (Online Compiler)

Open any online Java compiler (Programiz / JDoodle / OnlineGDB)

Copy-paste the entire code into one file

Make sure the main class is:

public class Main

Run the program

Use the menu to perform operations

📌 Sample Output ===== Student Management Menu =====

Add Student Delete Student Update Student Search Student View All Students Exit Enter your choice: 1 Enter Roll No: 78 Enter Name: hamza Email: 123456@email.com Enter Course: B.Tech Enter Marks: 78 Student added successfully!

🧠 Learning Outcomes

By completing this assignment, you will understand:

Abstract classes & inheritance

Interfaces & implementation

Method overloading vs overriding

Polymorphism (static & dynamic)

Managing objects using collections (HashMap)

Designing modular Java applications

👨‍💻 Author

Your Name Hamza Yusuf 2401010305 B.Tech CSE K.R. Mangalam University
