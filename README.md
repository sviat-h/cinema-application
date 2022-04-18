# :cinema: Cinema-Application :cinema:
### Project description:
`
A simple web-application that supports authentication, registration and other CRUD operations. You can check movie sessions, buy tickets, add new movies, etc.
`
## Endpoints:
- ``/register, /login`` Method-type: **POST**. Permissions: **ALL**.
- ``/movie-sessions/available,	/movies`` Method-type: **GET**. Permissions: **USER, ADMIN**
- ``/cinema-halls, /users/by-email`` Method-type: **GET**. Permissions: **ADMIN**
- ``/cinema-halls, /movie-sessions, /movies`` Method-type: **POST**. Permissions: **ADMIN**
- ``/movie-sessions/{id}`` Method-type: **PUT, DELETE**. Permissions: **ADMIN**
- ``/orders, /shopping-carts/by-user`` Method-type: **GET**. Permissions: **USER**
- ``/orders/complete`` Method-type: **POST**. Permissions: **USER**
- ``/shopping-carts/movie-sessions`` Method-type: **PUT**. Permissions: **USER**
## Project structure (3-layer architecture):
- DAO - Data access layer
- Service - Application logic layer
- Controllers - Presentation layer
## Used technologies and libraries:
- Java 11
- Git
- Apache Maven
- Apache Tomcat
- MySQL
- Spring MVC 
- Spring Security
- Hibernate
- Checkstyle plugin
## Steps to run the program on your computer:
- Clone the repo: [https://github.com/sviat-h/cinema-application.git](https://github.com/sviat-h/cinema-application.git);
- Install MySQL;
- Configure Apache Tomcat version (**IMPORTANT**): 9.0.xx;
- Configure [/src/main/resources/db.properties](/src/main/resources/db.properties) with your DB_URL, USERNAME, PASSWORD;
- Run the orogram;
- You already have two registered users: ``login: user@i.ua, pass: user1234, role: USER`` and ``login: admin@i.ua, pass: admin1234, role: ADMIN``;
- Done! Now just try to use it.:tada:
