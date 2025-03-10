The Leaky Cauldron - Magical Ecommerce Platform
Welcome to the Wizarding World of Ecommerce!
This repository contains the implementation of a modern, scalable ecommerce platform built using a microservices architecture with a Harry Potter theme. The system is designed to provide a seamless shopping experience with robust user management, product catalog, shopping cart, order processing, and payment features.
⚡ Magical Architecture
<img width="1176" alt="image" src="https://github.com/user-attachments/assets/08e83110-53e0-463f-bf71-b1e5f43d331e" />


The application is built on a Spring Boot microservices architecture with the following enchanted components:
🧙‍♂️ Core Services

[Diagon Alley - The Marketplace](https://github.com/the-leaky-cauldron/diagon-alley)

Product catalog management
Shopping cart functionality
Order processing
Payment services
"Where you can find anything your wizarding heart desires!"


[The Sorting Hat - User Management Service](https://github.com/the-leaky-cauldron/the-sorting-hat)

User registration and authentication
Profile management
Password reset functionality
User preferences
"Knows exactly where each user belongs!"


[The Nimbus API - API Gateway](https://github.com/the-leaky-cauldron/nimbus-api)

Request routing
"Swift and reliable, directing traffic with precision!"


[The Marauders Map - Service Discovery (Eureka)](https://github.com/the-leaky-cauldron/themaraudersmap)

Service registration
Health monitoring
Inter-service communication
"Solemnly showing where every service is and what it's up to!"


[The Pensieve - Outbox Pattern & Search Service](https://github.com/the-leaky-cauldron/the-penisive-scheduler)

Implements the outbox pattern for Diagon Alley
Manages Elasticsearch indexing for product search
Ensures data consistency between services
"Storing memories of transactions and making them searchable with a swish and flick!"

[The Daily Prophet's Owlery System - Notification Service](https://github.com/the-leaky-cauldron/the-daily-prophets-owlery-system)

Kafka-powered event consumption
Real-time notifications for users
Order status updates
Marketing communications
"Delivering news and updates with the speed and reliability of owl post!"

✨ Technical Spells (Tech Stack)

Framework: Spring Boot
Service Discovery: Netflix Eureka
API Gateway: Spring Cloud Gateway
Database: Postgres, Elastic search
Messaging: Kafka
Documentation: Swagger/OpenAPI
Containerization: Docker


