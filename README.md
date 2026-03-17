# 🚀 Task Manager Backend | Spring Boot REST API

<p align="center">
  <img src="https://media.giphy.com/media/13HgwGsXF0aiGY/giphy.gif" width="650"/>
</p>

A **RESTful Task Management Backend** built using **Spring Boot, Java, and JPA**.
This API allows users to perform **CRUD operations on tasks** and can be integrated with any frontend (React, Angular, etc.).

---

## 🛠 Tech Stack

![Java](https://img.shields.io/badge/Java-17-orange?logo=java)
![Spring Boot](https://img.shields.io/badge/SpringBoot-Backend-brightgreen?logo=springboot)
![JPA](https://img.shields.io/badge/JPA-Hibernate-blue)
![H2 Database](https://img.shields.io/badge/Database-H2-lightgrey)
![REST API](https://img.shields.io/badge/API-REST-green)

---

## ⚡ Features

✔ Create Task
✔ Get All Tasks
✔ Get Task by ID
✔ Update Task
✔ Delete Task
✔ RESTful API design
✔ In-memory H2 Database

---

## 🎬 Backend Workflow

```id="4k0q0x"
Client (Frontend / Postman)
            │
            ▼
        Controller Layer
            │
            ▼
        Service Layer
            │
            ▼
        Repository Layer
            │
            ▼
        Database (H2)
```

---

## 📂 Project Structure

```id="mllcxf"
task-manager-backend
│
├── controller
│     └── TaskController.java
│
├── service
│     └── TaskService.java
│
├── repository
│     └── TaskRepository.java
│
├── model
│     └── Task.java
│
├── TaskManagerApplication.java
│
└── resources
      └── application.properties
```

---

## 🔗 API Endpoints

| Method | Endpoint        | Description     |
| ------ | --------------- | --------------- |
| GET    | /api/tasks      | Get all tasks   |
| GET    | /api/tasks/{id} | Get task by ID  |
| POST   | /api/tasks      | Create new task |
| PUT    | /api/tasks/{id} | Update task     |
| DELETE | /api/tasks/{id} | Delete task     |

---

## ▶ How to Run the Project

### 1️⃣ Clone Repository

```id="63e31h"
git clone https://github.com/yourusername/task-manager-backend.git
```

### 2️⃣ Navigate to Project

```id="7jzpn6"
cd task-manager-backend
```

### 3️⃣ Run Application

```id="iqol07"
mvn spring-boot:run
```

---

## 🌐 API Base URL

```id="fjtt5m"
http://localhost:8080/api/tasks
```

---

## 🧪 Testing the API

You can test APIs using:

* Postman
* Thunder Client
* cURL

Example:

```id="t80g1k"
GET http://localhost:8080/api/tasks
```

---

## 💡 Future Improvements

* Add **JWT Authentication**
* Use **MySQL/PostgreSQL**
* Add **Pagination & Filtering**
* Implement **Exception Handling**
* Add **Docker support**

---

## 👨‍💻 Author

**Rishi Soni**

---

⭐ If you like this project, consider **starring the repository**.
