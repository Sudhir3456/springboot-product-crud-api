# 🛒 Product API : Spring Boot CRUD with MySQL

🚀 A robust and scalable Spring Boot-based RESTful API project designed to perform *CRUD operations on Product entities, integrated with **MySQL*, using clean architecture and modular design for better maintainability and scalability.

---

## 🎯 Objectives

- ✅ Develop RESTful APIs using Spring Boot  
- ✅ Perform end-to-end CRUD operations with MySQL database  
- ✅ Implement clean separation of concerns (Controller, DAO, Entity, Repository)  
- ✅ Ensure structured project architecture following best practices  
- ✅ Scalable codebase for real-time backend development and integration  

---
  
 # 📦 Spring Boot Simple CRUD with MySQL

A clean and modular Spring Boot project implementing CRUD operations with MySQL database integration.

## 🗂 Project Structure Overview
Pp# 📦 Spring Boot Simple CRUD with MySQL

A clean and modular Spring Boot project implementing CRUD operations with MySQL database integration.

## 🗂 Project Structure Overview

<table>
  <tr>
    <td valign="top" width="55%">

<pre>
spring-boot-simple-crud-with-mysql
├── src
│   ├── main/java
│   │   └── com.jspider.spring_boot_simple_crud_with_mysql
│   │       ├── controller
│   │       │   └── ProductController.java        # Handles HTTP requests (GET, POST, PUT, DELETE)
│   │       ├── dao
│   │       │   └── ProductDao.java               # Business logic layer for product operations
│   │       ├── entity
│   │       │   └── Product.java                  # Entity mapped to MySQL DB table
│   │       ├── repository
│   │       │   └── ProductRepository.java        # JPA Repository interface
│   │       ├── responses
│   │       │   └── ResponseStructure.java        # Custom response wrapper for consistency
│   │       └── SpringBootSimpleCrudWithMysqlApplication.java  # Main class
│
│   ├── main/resources
│   │   ├── application.properties                # DB config and server settings
│   │   ├── static                                # Static files (optional for front-end)
│   │   └── templates                             # Thymeleaf templates (if used)
│
│   └── test/java                                 # Unit and integration tests (to be added)
│
├── pom.xml                                       # Maven dependencies and plugins
├── HELP.md                                       # Spring generated project help
├── mvnw, mvnw.cmd                                # Maven wrapper
├── target                                        # Compiled build output
</pre>

</td>
<td valign="top" width="25%">
  <img src="https://github.com/user-attachments/assets/939712d2-7094-4447-a997-745471c46dbc" alt="Eclipse Project Structure" width="100%" />
</td>
</tr>
</table>
