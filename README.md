
# AuthService

This is a Spring Boot microservice for user authentication and authorization.

## Features

- User registration
- User login
- JWT token generation and validation

## Technology Stack

- Java 11
- Spring Boot
- Spring Security
- JPA (Hibernate)
- H2 Database (for development)

## Setup

1. Clone the repository.
2. Update `application.properties` with your database credentials.
3. Run the application.

```bash
./mvnw spring-boot:run
```

## Endpoints

- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - Authenticate a user and get a JWT
- `GET /api/user/me` - Get the authenticated user's details
