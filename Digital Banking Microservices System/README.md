💳 Digital Banking Microservices System
📌 Overview

This project is a Spring Boot Microservices-based Banking Application that simulates core banking operations such as user management, account handling, and fund transactions. The system is designed using a microservices architecture where each service is independently developed and deployed, ensuring scalability and maintainability.

🚀 Features
User registration and management
Account creation and management
Deposit and withdrawal operations
Fund transfer between accounts
Transaction history tracking
API Gateway for routing requests
Service Registry for service discovery
🏗️ Architecture

The application follows a microservices architecture, where each module is a separate service:

User Service → Handles user-related operations
Account Service → Manages bank accounts
Transaction Service → Handles transactions and transfers
API Gateway → Routes client requests
Service Registry (Eureka) → Enables service discovery

Services communicate with each other using REST APIs and Feign Clients.

🛠️ Tech Stack
Java
Spring Boot
Spring Cloud
Spring Data JPA
MySQL
Maven
Eureka Server
API Gateway
Postman (for API testing)
🔧 Enhancements / Modifications
Added basic validation to prevent invalid transactions
Improved error handling for better reliability
Structured APIs for better clarity and usability
▶️ How to Run
Clone the repository
Open the project in IntelliJ IDEA or Eclipse
Start services in order:
Service Registry (Eureka Server)
API Gateway
Other Microservices (User, Account, Transaction)
Use Postman to test APIs
📬 API Testing

You can test all endpoints using Postman by sending requests like:

Create User
Create Account
Transfer Funds
Get Transaction History
🎯 Learning Outcomes
Understanding of microservices architecture
Hands-on experience with Spring Boot and Spring Cloud
Service-to-service communication using Feign Client
API Gateway and service discovery implementation
📌 Future Improvements
Add authentication and authorization (Spring Security)
Implement real-time notifications
Dockerize the application
Add frontend interface
👨‍💻 Author

Charish Yadav