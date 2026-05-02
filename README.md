# 🛒 E-Commerce Web Application

A full-stack E-commerce web application built using **Java, Spring Boot, JSP, Servlets, and MySQL**.
This project provides a complete shopping experience with user authentication, product management, and admin control.

---

## 🚀 Features

### 👤 User Module

* User Registration & Login
* Browse Products
* Add to Cart & Purchase
* View Profile & Update Details

### 🛠️ Admin Module

* Admin Login
* Add / Update / Delete Products
* Manage Categories
* View Customer Details

---

## 🏗️ Tech Stack

* **Backend:** Java, Spring Boot
* **Frontend:** JSP, HTML, CSS
* **Database:** MySQL
* **Server:** Apache Tomcat
* **Architecture:** MVC (Model-View-Controller)

---

## 🗄️ Database Setup

1. Open MySQL Workbench
2. Run the following:

```sql
CREATE DATABASE springproject;
```

3. Import the file:

```
springproject.sql
```

---

## ⚙️ How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/AbhayUpadhyay1112/E-Commerce-SpringBoot.git
```

2. Open project in IntelliJ IDEA

3. Configure database in:

```
src/main/resources/application.properties
```

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/springproject
spring.datasource.username=root
spring.datasource.password=YOUR_PASSWORD
```

4. Run using Apache Tomcat Server

5. Open browser:

```
http://localhost:8080/
```

---

## 🔐 Login Credentials

### 👨‍💼 Admin

* URL: http://localhost:8080/admin
* Username: admin
* Password: 123

### 👤 User

* Username: Atharva
* Password: 1234

---

## 📌 Future Improvements

* REST API integration
* React frontend
* JWT Authentication
* Payment Gateway Integration

---

## 👨‍💻 Author

**Abhay Upadhyay**
GitHub: https://github.com/AbhayUpadhyay1112

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
