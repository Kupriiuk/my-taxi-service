# Taxi-Service
Web-application that supports driver authentication, registration and other CRUD operations with cars, manufacturers, drivers
# Features
- Login/Logout

- Registration of new drivers

- Adding new cars and manufacturers

- Assigning cars to drivers

- Displaying info about cars, drivers and manufacturers
# Technologies
- Java 11

- Maven

- MySql

- JDBC

- Tomcat (recommended version 9.0.50)

- JSP
# Project Structure
- Controller - accept http requests from users and display information

- Service - is responsible for the business logic of the application

- DAO - all the work with the database takes place at this level

# How launch the project:

- Fork this repository

- Clone this repository

- Create necessary database tables using init_db.sql

- Configure ConnectionUtil class
  ```
  private static final String URL = "URL";
  private static final String USERNAME = "USER NAME";
  private static final String PASSWORD = "PASSWORD";
  private static final String JDBC_DRIVER = "JDBC DRIVER";
  ``` 
- Install Tomcat (9.0.50)

- Add Tomcat server to configuration

- Run the project