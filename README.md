# CRUD Operation with Java Spring Boot

A RESTful CRUD API built with Spring Boot and JPA, providing basic user management operations.

## Tech Stack

- **Java 17**
- **Spring Boot 3.2.5**
- **Spring Data JPA**
- **H2 Database** (in-memory)
- **Maven**

## API Endpoints

| Method | Endpoint         | Description          |
|--------|------------------|----------------------|
| GET    | `/api/users`     | Get all users        |
| GET    | `/api/users/{id}`| Get user by ID       |
| POST   | `/api/users`     | Create a new user    |
| PUT    | `/api/users/{id}`| Update an existing user |
| DELETE | `/api/users/{id}`| Delete a user        |

## JSON Schema

### User

```json
{
  "id": 1,
  "name": "John Doe",
  "email": "john@example.com"
}
```

## Getting Started

### Prerequisites

- Java 17+
- Maven

### Run the application

```bash
mvn spring-boot:run
```

The server starts at `http://localhost:8080`. The H2 console is available at `http://localhost:8080/h2-console`.
