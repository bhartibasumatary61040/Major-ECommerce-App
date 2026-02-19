# Major E-Commerce App

project:
  name: Major E-Commerce Application
  description: >
    A complete backend e-commerce system built using Java and Spring Boot.
    It supports user authentication, product management, cart handling,
    order processing and payment gateway integration.

  purpose: >
    This project simulates a real-world online shopping platform like Amazon,
    where users can browse products, add to cart, place orders and complete payments securely.

features:
  authentication:
    - User registration and login
    - Spring Security based authentication
    - Role based access (Admin, User)

  product_management:
    - Add new products
    - Update existing products
    - Delete products
    - View product list

  cart_system:
    - Add items to cart
    - Remove items from cart
    - Checkout functionality

  order_processing:
    - Place orders
    - View order history

  payment:
    - Paytm payment gateway integration
    - Secure transaction handling

technology_stack:
  backend: Java, Spring Boot
  database: H2 In-Memory Database
  security: Spring Security, OAuth2
  frontend: Thymeleaf Templates
  build_tool: Maven
  utilities: Lombok

architecture:
  layered_structure:
    controller: Handles HTTP requests and APIs
    service: Contains business logic
    repository: Manages database interactions
    model: Entity classes representing tables

project_structure:
  src/main/java:
    - controller
    - service
    - repository
    - model

  src/main/resources:
    - templates
    - application.properties

setup:
  prerequisites:
    - Java 8 or higher
    - Maven installed

  steps:
    - git clone https://github.com/bhartibasumatary61040/Major-ECommerce-App.git
    - cd Major-ECommerce-App
    - mvn spring-boot:run

access:
  application_url: http://localhost:8080
  h2_console: http://localhost:8080/h2-console

database:
  type: H2
  purpose: Development and testing
  advantage: No external installation required

security_flow:
  - User registers and logs in
  - Password is encrypted
  - Role based authorization applied
  - Secured endpoints accessed

modules:
  user:
    - Signup
    - Login
    - Profile management

  product:
    - CRUD operations

  cart:
    - Add product
    - Remove product
    - Checkout

  order:
    - Place order
    - Order history

testing:
  framework: Spring Boot Test
  types:
    - Unit Testing
    - Integration Testing

future_enhancements:
  - JWT authentication
  - MySQL/PostgreSQL database
  - Admin dashboard
  - Product reviews
  - Email notifications


  name: Bharti Basumatary
  role: Automation Tester | Java | Selenium | Spring Boot
  github: https://github.com/bhartibasumatary61040

note:
  - This project follows industry standard layered architecture
  - Designed for learning and real-world backend practice

