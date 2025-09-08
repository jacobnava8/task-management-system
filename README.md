# ✅ Task Management System

## 📌 Overview
A **Java-based web application** for creating, tracking, and managing tasks.  
The system features **secure user authentication** and **role-based access control**, enabling multiple users to collaborate while protecting sensitive data.  

---

## 📂 Project Structure
📂 task-management-system
├── src/ # Java source code
├── web/ # HTML, CSS, JavaScript frontend
├── db/ # SQL schema and scripts
├── docs/ # Screenshots or architecture diagrams
└── README.md

yaml
Copy code

---

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/JacobNava/task-management-system
   cd task-management-system
   ```
2. Set up the database:

    -- Run db/schema.sql to create required tables.

3. Build and run the project (example using Maven):

```bash

mvn clean install
mvn spring-boot:run
```

(or use your IDE if not Maven-based)

Open in browser:

```arduino

http://localhost:8080
```
## 🛠️ Tech Stack
Backend: Java, JDBC (or Spring Boot if used)

Frontend: HTML5, CSS3, JavaScript

Database: SQL (MySQL/PostgreSQL)

Authentication: Secure login with password hashing

## 📊 Features
User Registration & Login

Role-Based Access (Admin / User)

Create, Update, Delete tasks

Task progress tracking dashboard

