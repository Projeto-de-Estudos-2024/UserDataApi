# User Registration API Project

This project is a user registration API developed in Java with the Spring Boot framework. It provides functionalities to create, retrieve, update and delete user information on a system.

## Features

- User registration
- Retrieval of user information
- Update user data
- Deletion of users

## Technologies used

- Java
- Spring Boot
- Spring Data JPA
- Spring MVC
- Banco de Dados: PostgreSQL

## Installing the development environment
- Start by installing Java version 17, in this [link](https://www.oracle.com/java/technologies/downloads/#jdk17-windows).

- To validate the java installation, open cmd and type this command:
```
java -version
```

- Install Maven, where you can find its latest version in this [link](https://maven.apache.org/download.cgi)
- To validate the maven installation, open cmd and type this command:
```
mvn -version
```
- If necessary, use [this tutorial](https://www.youtube.com/watch?v=w-D6hWXFcXw) of support.

- The IDE for coding in the Java language will be IntelliJ. To download it, access this [link](https://www.jetbrains.com/idea/download/?section=windows) in the community option.


## Getting Started

To start using the API, follow the steps below:

1. Clone the repository to your local machine.
2. Make sure you have Java and Maven installed.
3. Configure the database properties in the `application.properties` file.
4. Run the application using Maven: `mvn spring-boot:run`.
5. Access the API at `http://localhost:8080`.

## Explore the API

Full API documentation is available at [link to documentation].

## Request Examples

Below are some examples of how to interact with the API:

1. **User registration:**
   ```http
   POST /api/users
   Content-Type: application/json

   {
     "name": "Name User",
     "email": "user@example.com",
     "password": "password123"
   } 
   ```
2. **Search User by ID:**
```
GET /api/users/{id}
```

3. **User Update:** 
```
PUT /api/users/{id}
Content-Type: application/json

{
  "name": "New Name"
}
```
4. **User Deletion:**
```
DELETE /api/users/{id}
```

 ## Contribution Guidelines
Please read our contributing guidelines before you start contributing.

## Documentation
The complete documentation is available at [link to documentation].

## Report Problems
If you encounter any issues, please feel free to report it here.

## Guidelines for Pull Requests
Before submitting a pull request, make sure you follow the pull request guidelines.

## License
This project is licensed under the MIT License.