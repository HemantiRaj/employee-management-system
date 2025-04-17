# employee-management-system
HTML, CSS, Java, SQL

A web-based platform built with Java Servlets, MySQL, HTML, and CSS to manage employee records, authenticate users, and streamline administrative tasks.

Features

Secure Login Authentication (Session management)

CRUD Operations (Create, Read, Update, Delete employee records)

Interactive Admin Dashboard

Real-time Database Connectivity using JDBC

Client-side and Server-side Validations

Session Timeout Auto-Logout

Technologies Used

Frontend: HTML5, CSS3, (JavaScript for validations)

Backend: Java (Servlets)

Database: MySQL

Tools: NetBeans IDE, MySQL Workbench, Apache Tomcat Server

Project Structure

Admin-Management-System/
├── src/
│   ├── LoginServlet.java
│   ├── AddEmployeeServlet.java
│   ├── EditEmployeeServlet.java
│   ├── DeleteEmployeeServlet.java
│   ├── ViewEmployeeServlet.java
│   └── DBConnect.java
├── WebContent/
│   ├── login.html
│   ├── dashboard.jsp
│   ├── addEmployee.html
│   ├── editEmployee.jsp
│   └── viewEmployees.jsp
├── WEB-INF/
│   └── web.xml
├── README.md
└── (MySQL Database Script)

Installation and Setup

Clone the repository

git clone https://github.com/your-username/Admin-Management-System.git

Import the project into NetBeans IDE (or Eclipse).

Set up the MySQL database

Create a database named admin_db.

Run the provided SQL script to create tables: admin and employee.

Configure DB credentials

Update DBConnect.java with your MySQL username and password.

Deploy on Tomcat Server

Configure Apache Tomcat in your IDE.

Deploy the project and run.

Access the system

Open a browser and navigate to http://localhost:8080/Admin-Management-System/login.html

Database Schema

Admin Table

Column

Type

Description

id

INT (Primary Key)

Unique admin ID

username

VARCHAR

Admin login username

password

VARCHAR

Admin login password (hashed/plain)

Employee Table

Column

Type

Description

id

INT (Primary Key)

Unique employee ID

name

VARCHAR

Employee full name

email

VARCHAR

Contact email address

contact

VARCHAR

Contact number

department

VARCHAR

Department name

salary

DECIMAL

Monthly salary

Future Enhancements

Role-Based Access Control (Admin, HR, Manager roles)

Export Employee Data to PDF/Excel

Mobile Responsive Design

Cloud Hosting Support

Analytics Dashboard for employee insights

Screenshots

![image](https://github.com/user-attachments/assets/49ee1d7b-b84c-4cfd-bae8-6dbf3e5b6838)

![image](https://github.com/user-attachments/assets/2ce36d4f-62d4-4180-84fd-adbb11e94c93)

![image](https://github.com/user-attachments/assets/c0ee3d8b-50e2-4ccb-95db-2de6a10a8ece)

![image](https://github.com/user-attachments/assets/4633de47-e740-4378-8201-55161fb6fcfd)



