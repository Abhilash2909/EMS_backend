### EMS_backend

This is the backend of the Employee Management System (EMS) developed using **Spring Boot**. It provides RESTful APIs for employee management functionalities.

## Project Structure

- `src/`
  - `main/`
    - `java/`
      - `com/abhi/employment/`
        - **controller/**
          - **EmployeeController.java**: Exposes REST APIs for managing employees.
        - **dto/**
          - **EmployeeDto.java**: Data Transfer Object for employee data.
        - **entity/**
          - **Employee.java**: Represents the Employee entity.
        - **exception/**
          - **ResourceNotFoundException.java**: Custom exception for handling resource not found cases.
        - **mapper/**
          - **EmployeeMapper.java**: Maps between DTO and entity.
        - **repository/**
          - **EmployeeRepository.java**: Repository for performing CRUD operations on the Employee entity.
        - **service/**
          - **EmployeeService.java**: Contains business logic related to employees.
    - `resources/`
      - **application.properties**: Configuration properties for the application.

## How to Run the Application

1. **Install dependencies and build:**
   ```bash
   ./mvnw clean install
2. Run the application:
   ```bash
   ./mvnw spring-boot:run
3. The application will start on http://localhost:8080.

## Technologies Used

- **Spring Boot**
- **Java**
- **Maven (Build tool)**
- **MySQL**

