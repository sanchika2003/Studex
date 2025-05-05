# Studex
A Spring Boot web application for managing students, built with Java, Thymeleaf, Spring JPA, and H2 database. The application allows users to create, update, view, and delete student records with a responsive Bootstrap-based UI.

## 📌 Project Overview
You are responsible for backend operations to add and update student records, along with building responsive form pages for both features using Thymeleaf and Bootstrap.

---
 ## Features
1. Add new students with first name, last name, and email
2. View a list of all students in a tabular format
3. Update student details
4. Delete student records
5. User-friendly Bootstrap-based UI
6. Uses H2 in-memory database for easy setup
   
## Technologies Used
1.Java (Spring Boot)
2. Spring Web & Spring Data JPA
3. Thymeleaf (for dynamic HTML rendering)
4. H2 Database (in-memory database for quick prototyping)
5. Bootstrap 5 (for styling and responsive UI)

## Installation & Setup

1. JDK 17+
2. Maven
3. Git

## 🔧 Backend Responsibilities

- Set up application.properties:
  - Enable H2 console and JPA auto-update.
- Create StudentManagementApplication.java as the Spring Boot entry point.
- Implement controller methods in StudentController:
  - @GetMapping("/add") – Show add form.
  - @PostMapping("/add") – Save new student.
  - @GetMapping("/edit/{id}") – Show edit form.
  - @PostMapping("/update/{id}") – Save updated student.

---

## 🎨 Frontend Responsibilities

- Create add-student.html:
  - Form with fields: name, email, course.
  - Post form to /add.
- Create edit-student.html:
  - Pre-filled form for editing.
  - Post form to /update/{id}.
- Style both forms with Bootstrap for responsiveness.

