# cinema-app
### Project Description
This application represents work of cinema's ticket-reservation system and has next functions:

- registration of user and signing in
- authorization based on roles
- adding tickets to the shopping cart
- basic CRUD operations, find by parameters

All endpoints send and receive JSON data, except the login page. Almost all endpoints are secured by role-based authorization.

### Project architecture
1. Presentation layer
2. Service layer
3. Data access layer

### Database structure 
![](structure.png)

### Technologies used in project

- Java 11
- Apache Maven v3.8
- Apache tomcat v9
- MySQL v8
- Spring Core 5.2.2
- Spring MVC 5.2.2
- Spring Security 5.2.2
- Hibernate v5

### How to install and configure

1. Clone this project
2. Install and configure MySQL and Apache Tomcat
3. Setup DB parameters in resources/db.properties
4. To inject default roles send GET request to http://localhost:8080/inject
5. Now you can log in as an admin with the following credentials: (email: admin@i.ua, password: admin123)
