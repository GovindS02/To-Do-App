
# To-Do App – Full Stack Task Manager (Spring Boot + SQL + JPA)

A full-stack To-Do / Task Management application built using **Java Spring Boot**, **Thymeleaf**, **Spring Data JPA**, and **SQL**.  
Users can create, update, delete tasks and mark tasks as completed.

✅ Working full-stack project using Thymeleaf  
🚀 Currently upgrading frontend to **React** while keeping backend stable

---

## Features
- Add a new task
- Edit/update task
- Delete task
- Mark task as completed
- Track task status (Pending/Completed)
- Validation and basic error handling

---

## Tech Stack
### Backend
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA (Hibernate)

### Database
- MySQL / PostgreSQL (SQL)

### Frontend
- Thymeleaf
- HTML/CSS/JavaScript
- (Upgrade in progress: React.js)

### Tools
- Git / GitHub
- Postman (API testing)

---

## Setup Instructions

### Prerequisites
- Java (17+ recommended)
- Maven
- MySQL/PostgreSQL installed locally

---

## Database Configuration (Safe Public Setup)

⚠️ Never commit real DB credentials in public repos.

### Option A (Simple Local Setup)
Edit `src/main/resources/application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/todo_db
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
