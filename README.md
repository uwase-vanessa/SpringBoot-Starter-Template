# Spring Boot NE Template 2025

This is a Spring Boot template project for 2025 using Java 24.

## Overview

This template provides a basic structure for building Spring Boot applications with Jakarta EE and Spring MVC.

## Technical Stack

- Java 24
- Spring Boot 3.4.5
- Jakarta EE
- Spring MVC
- Maven

## Getting Started

### Prerequisites

- JDK 24
- Maven 3.8+

### Running the Application

1. Clone the repository
2. Navigate to the project directory
3. Run the application using Maven:

mail docker 

docker run -d --name redis-container -p 6379:6379 redis:alpine redis-server --requirepass spring-redis-password
docker exec -it redis-container redis-cli -a spring-redis-password
# Redis configuration
spring.data.redis.port=6379
spring.data.redis.host=localhost
spring.data.redis.password==spring-redis-password
spring.cache.type=redis
