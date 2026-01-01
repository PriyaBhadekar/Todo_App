📝 Todo Application – Spring Boot

A simple Todo Application built using Spring Boot that allows users to manage daily tasks efficiently.
This project demonstrates backend development with Spring Boot, PostgreSQL, Spring Data JPA, and server-side rendering using Thymeleaf.

--------------------------------------------------------------------------------------------------------------------------------------------------------

🚀 Features

Create new todo tasks
View all todos
Update existing tasks
Delete tasks
Persistent data storage using PostgreSQL
MVC-based clean architecture

--------------------------------------------------------------------------------------------------------------------------------------------------------

🛠 Tech Stack

Java
Spring Boot
Spring Web
Spring Data JPA
PostgreSQL
Lombok
Thymeleaf
Maven

--------------------------------------------------------------------------------------------------------------------------------------------------------

📂 Project Structure
src/
 └── main/
     ├── java/
     │   └── com.example.todo
     │       ├── controller
     │       ├── service
     │       ├── repository
     │       └── model
     └── resources/
         ├── templates
         ├── static
         └── application.properties

--------------------------------------------------------------------------------------------------------------------------------------------------------

🗄 Database Configuration (PostgreSQL)

Update application.properties:

spring.datasource.url=jdbc:postgresql://localhost:5432/tododb
spring.datasource.username=your_username
spring.datasource.password=your_password

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect

--------------------------------------------------------------------------------------------------------------------------------------------------------

▶️ How to Run the Application
Prerequisites
Java 17 or higher
Maven
PostgreSQL

Steps
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
mvn spring-boot:run


Access the application at:
http://localhost:8080

📌 Dependencies Used
Spring Web
Spring Data JPA
PostgreSQL Driver
Lombok
Thymeleaf

--------------------------------------------------------------------------------------------------------------------------------------------------------

🎯 Learning Outcomes

Built a complete CRUD-based Spring Boot application
Integrated PostgreSQL with Spring Data JPA
Used Lombok to reduce boilerplate code
Implemented MVC pattern using Thymeleaf
Gained hands-on experience with backend development

--------------------------------------------------------------------------------------------------------------------------------------------------------

📄 License

This project is developed for learning and educational purposes.

✨ Author

Priya Bhadekar
Java & Spring Boot Developer
