# 📚 Quiz-App | Team: CodeQuizzers

A full-stack Quiz Application built using **Spring Boot** for the backend. Designed to manage quiz questions, evaluate answers, and provide an interactive platform for users. This project is a part of our learning journey in building real-world applications using Java and Spring technologies.

---

## 🚀 Tech Stack
- **Java**
- **Spring Boot**
- **Spring Web**
- **Spring Data JPA**
- **MySQL** (or H2 for in-memory testing)
- **Maven**
- **Postman** (for testing REST APIs)

---

## 🎯 Features
- Add, edit, and delete quiz questions
- REST APIs to fetch and submit questions
- JSON-based question/answer handling
- Store data in a relational database (MySQL)
- Clean, scalable project structure
- Ready to integrate with frontend (React, Angular, or Thymeleaf)

---

## 📁 Project Structure

quiz-app/ ├── src/ │
          ├── main/ │
          │ ├── java/io/github/shivamsikarwar/quizapp/ │
          │ │ ├── controller/ │
          │ │ ├── service/ │
          │ │ ├── model/ │
          │ │ └── QuizAppApplication.java │
          │ └── resources/ │
          │ ├── application.properties │
          │ ├── static/ │
          │ └── templates/
          ├── test/ 
          ├── pom.xml 
          └── README.md


---

## ⚙️ How to Run Locally

1. **Clone the Repo:**
   ```bash
   git clone https://github.com/ShivamSikarwar/quiz-app.git
   cd quiz-app


Configure Databse-
spring.datasource.url=jdbc:mysql://localhost:3306/quiz_db
spring.datasource.username=root
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update


Run the App:
In IntelliJ, run QuizAppApplication.java



Test Endpoints:

Open Postman
Use:
GET http://localhost:8080/api/questions
POST http://localhost:8080/api/questions

📸 Screenshots
(Add screenshots of your app UI or Postman tests if you want)

📬 Contact
For any questions or suggestions:
📧 Email: [Shivamsikarwar6396@gmail.com 
🌐 GitHub: [github.com/shivamsikarwar]



