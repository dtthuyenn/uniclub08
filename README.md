# UniClub - Clothing E-commerce Website

## 📌 Introduction

UniClub is an online clothing store website for selling T-shirts and hoodies.
This project is developed as an academic project.

---

# ⚙️ Technologies

* Backend: Spring Boot
* Database: MySQL
* ORM: Spring Data JPA
* Build Tool: Maven

---

# 🗄️ Database Configuration

Create a MySQL database named **uniclub**.

```sql
CREATE DATABASE uniclub;
```

---

# 🔧 Application Configuration

Update the **application.yml** file in `src/main/resources`.

```yaml
server:
  port: 8080

spring:
  datasource:
    url: jdbc:mysql://localhost:3307/uniclub
    username: root
    password: admin123
  jpa:
    hibernate:
      ddl-auto: none
```

### Explanation

| Property       | Description                                  |
| -------------- | -------------------------------------------- |
| server.port    | Port used to run the Spring Boot application |
| datasource.url | MySQL database connection                    |
| username       | MySQL username                               |
| password       | MySQL password                               |
| ddl-auto       | Database schema strategy                     |

---

# 🚀 How to Run the Project

### 1️⃣ Clone repository

```bash
git clone https://github.com/your-username/uniclub.git
```

### 2️⃣ Open project

Open the project using **IntelliJ IDEA** or **VS Code**.

### 3️⃣ Configure database

Make sure MySQL is running and the database **uniclub** exists.

### 4️⃣ Run the application

Run the Spring Boot project.

Or using Maven:

```bash
mvn spring-boot:run
```

### 5️⃣ Access API

```
http://localhost:8080
```

---

# 👨‍💻 Author

Software Engineering Student Project
