# CRUD Operations Using Spring Framework

This repository contains a project showcasing **CRUD (Create, Read, Update, Delete) operations** implemented using the **Spring Framework**. The application demonstrates fundamental database management functionalities with a simple and scalable architecture.

---

## Features

- **Create**: Add new records to the database.
- **Read**: Retrieve and view records from the database.
- **Update**: Modify existing records with ease.
- **Delete**: Remove records from the database.
- **User-Friendly API**: Simple endpoints for performing CRUD operations.

---

## Technologies Used

- **Framework**: Spring Boot
- **Programming Language**: Java
- **Database**: MySQL
- **Tools**: Spring Data JPA, Hibernate, Maven
- **API Documentation**: Swagger (Optional)

---

## Setup Instructions

### Prerequisites

Ensure you have the following installed on your system:

- Java Development Kit (JDK 8 or higher)
- MySQL Server
- Maven (for dependency management)
- An IDE (e.g., IntelliJ IDEA, Eclipse) for Java development

### Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/amit-soham-16/Crud-Operation-using-spring.git
   cd Crud-Operation-using-spring
   ```

2. **Configure Database**
   - Create a MySQL database named `crud_db`.
   - Update the `application.properties` file with your MySQL credentials:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/crud_db
     spring.datasource.username=YOUR_USERNAME
     spring.datasource.password=YOUR_PASSWORD
     spring.jpa.hibernate.ddl-auto=update
     ```

3. **Build and Run the Application**
   - Build the project using Maven:
     ```bash
     mvn clean install
     ```
   - Run the Spring Boot application:
     ```bash
     mvn spring-boot:run
     ```

4. **Access the API**
   - The application runs on `http://localhost:8080` by default.
   - Use tools like Postman or your browser to interact with the endpoints.

---

## API Endpoints

### Base URL: `http://localhost:8080`

- **Create a Record**
  - Method: `POST`
  - Endpoint: `/create`

- **Retrieve All Records**
  - Method: `GET`
  - Endpoint: `/read`

- **Retrieve a Single Record by ID**
  - Method: `GET`
  - Endpoint: `/read/{id}`

- **Update a Record**
  - Method: `PUT`
  - Endpoint: `/update/{id}`

- **Delete a Record**
  - Method: `DELETE`
  - Endpoint: `/delete/{id}`

---

## Project Structure

- `src/main/java`
  - Contains all Java source files for controllers, services, and repositories.
- `src/main/resources`
  - `application.properties`: Configuration file for database and application settings.
- `pom.xml`
  - Maven configuration file for managing dependencies.

---


## Contact

For any queries or feedback, please reach out:

- **Amit Kumar**
- [GitHub Profile](https://github.com/amit-soham-16)
- Email: [amitk1602info@gmail.com](mailto:amitk1602info@gmail.com)
