# 🎓 Student Management System - Spring Boot REST API

This is a **Student Management System** built using **Spring Boot** that provides a complete RESTful API for managing student data. The application allows you to perform CRUD operations such as adding, viewing, updating, and deleting student information.

## 🛠️ Technologies Used

- **Backend**: Java, Spring Boot, Spring Web, Spring Data JPA
- **Database**:  MySQL 
- **Testing Tool**: Postman
- **Build Tool**: Maven

##  Project Structure

student-management-system/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com.example.student/
│ │ │ ├── controller/
│ │ │ ├── service/
│ │ │ ├── repository/
│ │ │ └── entity/
│ │ └── resources/
│ │ └── application.properties
├── pom.xml
└── README.md


## 📌 Features

- Add a new student
- View all students
- Get student by ID
- Update student details
- Delete a student
- Proper status codes and JSON responses
- Input validation and exception handling

## 🔗 API Endpoints

| Method | Endpoint             | Description             |
|--------|----------------------|-------------------------|
| GET    | `/students`          | Get all students        |
| GET    | `/students/{id}`     | Get student by ID       |
| POST   | `/students`          | Add a new student       |
| PUT    | `/students/{id}`     | Update student by ID    |
| DELETE | `/students/{id}`     | Delete student by ID    |

## 🧪 API Testing with Postman

You can use [Postman] to test the API. A sample Postman collection can be created with the following sample data:

### 📤 POST `/students`

```json
sample example :-
{
  "name": "Sneha Sabde",
  "email": "sneha@example.com",
  "course": "Computer Engineering"
}


