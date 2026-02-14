# 🍽️ Recipe Management API

RESTful API for managing recipes and users with secure authentication and role-based access control.

## 🚀 Features
- Full CRUD for recipes and users
- JWT authentication & role-based authorization
- Secure client–server communication
- RESTful endpoints tested with Insomnia
- MongoDB persistence

## 🧰 Tech Stack
- Java, Spring Boot
- MongoDB
- Spring Security, JWT
- Maven

## 📁 Project Structure
- `src/main/java` – API source code  
- `src/main/resources` – configs  
- `pom.xml` – dependencies  
- `mvnw` – Maven wrapper


## ▶️ How to Run Locally
1. Configure MongoDB connection in `application.properties`  
2. Start the server:
```bash
./mvnw spring-boot:run

Test endpoints using Insomnia or Postman

##🔐 Auth
Register user → receive JWT
Pass token in header:
Authorization: Bearer <token>

##🧠 What I Learned
Designing RESTful APIs
Securing endpoints with JWT
Role-based access control
MongoDB schema design
Professional Git/GitHub workflow

##👩‍💻 Author
Malak Faour
