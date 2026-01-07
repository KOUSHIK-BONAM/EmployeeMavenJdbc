# Employee Management System (Java JDBC + Maven)

This is a **console-based Employee Management System** developed using **Java, JDBC, Maven, and MySQL**.  
The project demonstrates CRUD operations with database connectivity and follows the **DAO design pattern**.

---

## 🚀 Features
- User login authentication
- Insert employee records
- View all employees
- View employee by ID
- Update employee details
- Delete employee records

---

## 🛠️ Technologies Used
- Java (JDK 21+)
- Maven
- JDBC
- MySQL (via XAMPP)
- phpMyAdmin

---

## 🗄️ Database Structure

### Database Name
skill_db

### Users Table
```sql
CREATE TABLE users (
    username VARCHAR(50) PRIMARY KEY,
    password VARCHAR(50)
);

PROJECT STRUCTURE 
MyExWeb
├── src
│   └── main
│       ├── java
│       │   └── com.example
│       │       ├── DBUtil.java
│       │       ├── LoginDAO.java
│       │       ├── EmployeeDAO.java
│       │       └── MainApp.java
│       └── webapp
│           └── WEB-INF
│               └── web.xml
├── pom.xml
└── README.md

Academic Note

This project was developed as part of a college lab / academic assignment to demonstrate JDBC connectivity and Maven project structure.