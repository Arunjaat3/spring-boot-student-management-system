🎓 Student Management System

A full-stack web application built using Spring Boot, MySQL, HTML, and CSS that allows users to manage student records efficiently. This project demonstrates basic CRUD (Create, Read, Update, Delete) operations with a clean and user-friendly interface.

🚀 Features

➕ Add new students

📋 View list of students

✏️ Update student details

❌ Delete student records

💾 Data stored in MySQL database

🎯 Simple and responsive UI

🛠️ Tech Stack

Backend: Spring Boot, Java

Frontend: HTML, CSS, Bootstrap

Database: MySQL

ORM: JPA / Hibernate

📂 Project Structure

Controller Layer – Handles HTTP requests

Service Layer – Business logic

Repository Layer – Database operations

Entity Class – Represents Student data

⚙️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/spring-boot-student-management-system.git

Open project in your IDE (IntelliJ / Eclipse)

Configure MySQL in application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=root
spring.datasource.password=your_password

Run the Spring Boot application

Open browser and go to:

http://localhost:8080/students
