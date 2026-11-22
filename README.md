Autoloc API

 Project Description

Autoloc API is a Spring Boot application for a vehicle rental management system.

This project is developed as part of the ECE Spring Boot workshop.

 Technologies Used

- Java 17
- Spring Boot
- Maven
- Spring Data JPA
- Hibernate
- MySQL
- Lombok
- Jakarta Validation

 Project Structure

```text
src/
 ├── main/
 │   ├── java/fr/ece/autoloc_api/
 │   │   ├── domain/
 │   │   ├── repository/
 │   │   ├── service/
 │   │   └── web/
 │   └── resources/
 │       ├── application.properties
 │       └── application-example.properties
 └── test/
```

 Database Configuration

The application uses MySQL.

Database name: `autoloc_db`

Before running the application:

1. Install and start MySQL.
2. Configure your database credentials in `src/main/resources/application.properties`.
3. Never upload your real database password to GitHub.

You can use `application-example.properties` as a configuration reference.

Implemented So Far

- Spring Boot project initialization.
- MySQL database configuration.
- JPA and Hibernate configuration.
- Vehicle category enum (`CategorieVehicule`).
- Vehicle status enum (`StatutVehicule`).
- Vehicle entity (`Vehicule`).

 Run the Application

Using Maven Wrapper:

Windows:

powershell
.\mvnw.cmd spring-boot:run


Mac/Linux:

bash
./mvnw spring-boot:run


 Author

ECE Spring Boot Workshop Project
