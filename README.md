# DictionaryApp

This is a simple Spring Boot project called DictionaryApp, designed to demonstrate the usage of Spring Boot, Thymeleaf, and Spring Data JPA. It provides a basic setup for creating a web application.

## Prerequisites
- Java 11
- Maven

## Dependencies
- **Spring Boot Starter Data JPA**: Provides support for JPA (Java Persistence API) including data access, transactions, and more.
- **Spring Boot Starter Thymeleaf**: Integrates Thymeleaf into Spring Boot, enabling server-side rendering of HTML templates.
- **Spring Boot Starter Validation**: Adds support for validating data in Spring Boot applications.
- **Spring Boot Starter Web**: Includes common web dependencies like Spring MVC and embedded Tomcat server.
- **Spring Boot DevTools**: Provides development-time features like automatic restarts and enhanced development experience.
- **MySQL Connector/J**: Allows connecting to MySQL database from Java applications.
- **Spring Boot Starter Test**: Includes testing dependencies for Spring Boot applications.
- **Spring Security Crypto**: Provides cryptographic utilities for Spring Security.
- **Hibernate JPA 2.1 API**: Hibernate implementation of JPA 2.1 API.
- **Jakarta Persistence API**: Jakarta Persistence API (formerly Java Persistence API) provides a specification for object-relational mapping.
- **Jakarta Validation API**: Jakarta Bean Validation (formerly Bean Validation) API for validation of JavaBeans.

## Building and Running
To build the project, make sure you have Maven installed and then execute:
```bash
mvn clean install
```

To run the application:
```bash
java -jar target/DictionaryApp-0.0.1-SNAPSHOT.jar
```

## Usage
Once the application is running, you can access it via a web browser at the specified URL (typically `http://localhost:8080`). This application serves as a starting point for building a dictionary application with basic CRUD (Create, Read, Update, Delete) operations.

## Author
Stanimir Sergev (SNS)

## License
This project is licensed under the [MIT License](LICENSE).

