# Messaging App - Spring Boot REST API

## 📌 Project Overview
Messaging App is a simple Spring Boot REST API project created to demonstrate different types of HTTP requests such as GET, POST, PUT along with Query Parameters, Path Variables, and Request Body handling.

This project is mainly for learning and practicing Spring Boot REST controller concepts.

---

## 🛠 Tech Stack
- Java
- Spring Boot
- Spring Web
- Maven

---

## ⚙️ Features
✔ Simple GET API  
✔ GET API using Query Parameter  
✔ GET API using Path Variable  
✔ POST API using Request Body  
✔ PUT API using Path Variable + Query Parameter  

---

## 📡 API Endpoints

### 1️⃣ Simple Hello API
GET  
/hello  

Response:
Hello from BridgeLabz

---

### 2️⃣ Hello Using Query Parameter
GET  
/hello/query?name=Aryan  

Response:
Hello Aryan from BridgeLabz

---

### 3️⃣ Hello Using Path Variable
GET  
/hello/param/Aryan  

Response:
Hello Aryan from BridgeLabz

---

### 4️⃣ Hello Using POST Request
POST  
/hello/post  

Request Body:
{
  "firstName": "Aryan",
  "lastName": "Sarthak"
}

Response:
Hello Aryan Sarthak from BridgeLabz

---

### 5️⃣ Hello Using PUT Request
PUT  
/hello/put/Aryan?lastName=Sarthak  

Response:
Hello Aryan Sarthak from BridgeLabz

---

## 🚀 How To Run

### Clone Repository
git clone https://github.com/your-username/messaging-app.git  

### Navigate To Project
cd messaging-app  

### Build Project
mvn clean install  

### Run Application
mvn spring-boot:run  

---

## 🧪 Testing
You can test APIs using:
- Postman
- Browser (for GET APIs)

---

## 🧑‍💻 Author
Aryan Sarthak  

---

## 📄 License
This project is for learning and practice purposes.
