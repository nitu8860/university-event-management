# University-event-management
## Frameworks and language used:
-This project is built using Java, with the Spring Boot framework.

-The web framework used in the project is Spring MVC.

-The persistence layer uses JPA and Hibernate to interact with the database.

-The database used in this project is H2, an in-memory relational database.

## Data flow
The data flow in this project follows the MVC pattern, with the following components:

Controller: The controllers handle incoming HTTP requests, process the data, and return the appropriate response.

Services: The services contain the business logic of the application. They receive data from the controllers, process it, and return the results to the controllers.

Repository: The repositories interact with the database to persist and retrieve data. They receive requests from the services, execute the required database operations, and return the results to the services.

Database Design: The database used in this project is H2, and it is designed using the Entity-Relationship (ER) model. The database has two tables: one for events and one for student. The event table contains information about each event, such as its name, location, date, start time, end time, and image URL. The student table contains information about name,age, department.

## Data Structure

The project uses H2 console to view the data in the database, and also uses Swagger UI to test the API endpoints.
H2 console:http://localhost:8080/h2-console/login.do?jsessionid=6d290c4291c492969bb99874ce29468b

Swagger UI:http://localhost:8080/swagger-ui/index.html

## Project Summary

This project is a university event management system. It allows the user to manage events and tasks. The user can create, read, update, and delete events and tasks, view their details, and mark tasks as completed. The project uses a combination of Java, Spring Boot, Spring MVC, JPA, and Hibernate to build a web-based application that interacts with a database.
