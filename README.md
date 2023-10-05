## Overview

The goal of the "Restaurant Management" project is to create a simple Spring Boot application for managing restaurant information. This includes functionalities such as retrieving restaurants by ID, getting a list of all restaurants, adding new restaurants, updating restaurant information, and deleting restaurants.

## Technologies Used

- **Framework:** Spring Boot
- **Language:** Java
- **Build Tool:** Maven

## Dependencies

The Restaurant Management uses the following dependencies:

- **Spring Boot Starter Web**
  - **Description:** Provides support for building web applications, including RESTful APIs.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>
    ```
- **Project Lombok (Optional)**
  - **Description:** A library that simplifies Java code by reducing boilerplate code, such as getters and setters.
  - **Maven Dependency:**
    ```xml
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <optional>true</optional>
    </dependency>
    ```

- **Spring Boot Starter Test (For Testing)**
  - **Description:** Provides support for testing Spring Boot applications.
  - **Maven Dependency (Test Scope):**
    ```xml
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-test</artifactId>
        <scope>test</scope>
    </dependency>
    ```

## Data Flow

In the E-commerce API application, data flows through various components to handle operations related to different entities, including users, products, orders, and addresses. Here's an overview of the data flow for each entity:

1. **Restaurant Entity**

   - **Controller Layer**

     The Controller layer handles user-related HTTP requests and routes them to the appropriate service methods.

     ```java
     // Controller.java

     @RestController
    
     public class Controller {
         // Define restaurant endpoints and methods
     }
     ```

   - **Service Layer**

     The Service layer contains business logic and interacts with the restaurant Repository to perform CRUD operations on user data.

     ```java
     // Service.java

     @Service
     public class RestaurantService {
         // Implement Restaurant-related service methods
     }
     ```

   - **Repository Layer**

     The Repository layer manages data access to the entity using Spring Data In List.

     ```java
     // RestaurantRepo.java

     @Repository
     public class RestaurantRepo {
	 @Auto wired
         // Define Object of list of Restaurant and creating method of list type which would return list of restaurant
     }
     ```

   - **Entity**

     The Entity represents the structure of Restaurant data in the database(List).

     ```java
     // Restaurant.java ( Entity)

     @Entity
     public class Restaurant {
         // Define Restaurants attributes, getters, setters, etc.
     }
     ```     


## Data Structures Used

The project utilizes List data structures as data base:


## Project Summary

This "Restaurant Management" project is to create a simple Spring Boot application for managing restaurant information. This includes functionalities such as retrieving restaurants by ID, getting a list of all restaurants, adding new restaurants, updating restaurant information, and deleting restaurants.

