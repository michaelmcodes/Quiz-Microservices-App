# Quiz-Microservices-App

This repository contains a Spring Boot microservices application with two different services and a Eureka server.

## Technologies Used
- Spring Boot
- Spring Data JPA
- JDBC
- Microservices
- Eureka
- Open Feign

## Project Structure

- **Quiz-Service**: This is the first microservice responsible for creating the quizzes.
- **Question-Service**: This is the second microservice responsible for creating the questions.
- **eureka-server**: This is the Eureka server that helps with service discovery.

## How to Run

1. **Start the Eureka Server**:
   Navigate to the `eureka-server` directory and run the application:
   cd quiz-serviceregistry
   ./mvnw spring-boot:run
2. **Start Question-Service**:
   cd question-service
   ./mvnw spring-boot:run
3. **Start Quiz-Service**:
   cd quiz-service
   ./mvnw spring-boot:run
