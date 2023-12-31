# taxi-service 🚖

A simple web-application that supports authentication, registration, and other CRUD operations.

## Features:

- register like a driver;
- authentication like a driver;
- create/update/remove a driver;
- display list of all drivers
- create/update/remove a car;
- display list of all cars;
- create/update/remove a manufacturer;
- display list of all manufacturers;
- add a driver to a car;
- display list of all cars for current login driver;

## Project structure:

- DAO (Data Access Object) - DAO is the data access layer responsible for interacting with the database. This layer
  implements operations related to retrieving, storing, updating, and deleting data.
- Service - The service layer is responsible for the business logic of the application. It handles data processing,
  executes business rules, and coordinates actions between the DAO and other components of the application.
- Controller - The Controller layer serves as the entry point for external requests to the application.

## Used technologies:
- Java 11
- Tomcat 9.0.76
- MySQL 8.0.22
- Maven 3.1.1
- Java Servlet 4.0.1
- JSTL 1.2
- JSP 
- JDBC

## Instructions for launching the project:
1. Fork this project;
2. Clone the project from GitHub;
3. Install Apache Tomcat version 9.x.x.
4. Create all required tables. Use code from init_db.sql;
5. In the ConnectionUtil class, fill in the URL, username, password and JDBC driver fields with the necessary data.
6. Configurate Tomcat;
7. Run the project.




