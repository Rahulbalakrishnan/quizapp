# QuizApp 

Welcome to QuizApp, a Java-based backend quiz application built with Spring Boot, Spring MVC, and PostgreSQL. 

## Overview

QuizApp follows a layered architecture design, consisting of the following layers:

1. **User Interface (User):** The front-end layer where users interact with the application.
2. **Controller:** Manages the flow of data between the user interface and the service layer.
3. **Service:** Contains the business logic and acts as an intermediary between the controller and the DAO layer.
4. **DAO (Data Access Object):** Responsible for interacting with the database.
5. **Database:** Utilizes PostgreSQL to store and retrieve quiz-related data.

## Technologies Used

- Java 
- Spring Boot 
- Spring MVC 
- PostgreSQL 
- Lombok - A small library that was used to reduce the unused code from the java applications.
  It wil automatically generating the getter and setter method for the class object by using Lombok annotation.
  It is not limited to setting getter readme more: (https://projectlombok.org/features/)

## Configuration

Make sure to update the `application.properties` file based on your settings:

```properties
spring.datasource.driver-class-name=org.postgresql.Driver
spring.datasource.url=jdbc:""
spring.datasource.username=postgres
spring.datasource.password=""
spring.jpa.hibernate.ddl-auto=update
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.PostgreSQLDialect
```
Adjust the values according to your local environment and database setup.

Happy Coding!!
