
# RBAC Authentication and Authorization System

This project demonstrates a simple role-based access control (RBAC) system using Spring Boot and JWT for user authentication and authorization.

## Features
1. **Authentication**: Users can register, login, and get a JWT token.
2. **Authorization**: Roles such as `ADMIN`, `USER` are used to protect specific resources.
3. **RBAC**: Access to resources is determined based on roles.

## How to run
1. Set up the database (H2 or MySQL).
2. Configure `application.properties` with the appropriate database connection settings.
3. Build the project using Maven (`mvn clean install`).
4. Run the application (`mvn spring-boot:run`).
