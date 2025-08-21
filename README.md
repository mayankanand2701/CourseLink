# CourseLink

## 📌 Project Overview
This project is a **CourseLink** built using **Spring Boot** and **Spring Data JPA**.  The primary goal of this project is to **understand how entity relationships (One-to-One, One-to-Many, Many-to-Many) work in JPA** and how to design REST APIs for CRUD operations.  

Additionally, it demonstrates **Exception Handling** in REST APIs and **unit testing with Spring Test & Mockito**.  

## ⚙️ Features
- Student management (Add, Update, Delete, Get)  
- Course management (Add, Update, Delete, Get)  
- Enroll students in courses  
- View all courses of a student  
- View all students enrolled in a course  
- Exception handling for invalid requests (e.g., student or course not found)  
- Tested using **Spring Boot Test** and **Mockito**  

## 🔗 API Endpoints
### Student APIs
- `POST /api/students` → Add a new student  
- `GET /api/students/{id}` → Get student by ID  
- `GET /api/students` → Get all students  

### Course APIs
- `POST /api/courses` → Add a new course  
- `GET /api/courses/{id}` → Get course by ID  
- `GET /api/courses` → Get all courses  

### Enrollment APIs
- `POST /api/enrollments` → Enroll a student in a course  
- `GET /api/students/{id}/courses` → Get all courses of a student  
- `GET /api/courses/{id}/students` → Get all students in a course  


## 🛠️ Tech Stack
- Java 17  
- Spring Boot 3  
- Spring Data JPA (Hibernate)  
- H2 Database (for testing) / MySQL (optional)  
- Spring Test & Mockito for unit testing  

## 🧪 Testing
- Used **JUnit 5 & Spring Boot Test** for testing REST APIs.  
- Used **Mockito** for mocking service layer in unit tests.  
