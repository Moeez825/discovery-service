# discovery-service

The Discovery Service is a component in the Instagram clone application that provides service discovery and registration functionality. It allows microservices within the system to dynamically register themselves and discover other services. The Discovery Service acts as a central registry that keeps track of all the available services and their network locations.

## Features

- Service registration and discovery
- Load balancing and routing

## Getting Started

These instructions will get you a copy of the Discovery Service up and running on your local machine for development and testing purposes.

## Technologies Used
- Java 17
- Spring Boot 3.1.0
- Maven 4.0.0
## Dependencies

- [Spring Boot] 
- [Spring Cloud Eureka]

### Prerequisites

- [Java SE Development Kit 17.0.5] (https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
- [Maven 4.0.0] (https://maven.apache.org/install.html)
- [Spring Boot CLI] (https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#getting-started-installing-the-cli) (Optional)

### Installation
1. Clone the repository:
```bash
git clone <repository-url>
```
2. Navigate to the project directory::
```bash
cd discovery-service
```
3. Build the project using Maven:
```bash
cd discovery-service
```
4. Run the application:
```bash
mvn spring-boot:run
```
## Configuration
The Discovery Service requires configuration to define service registration, discovery, and health check settings. Here are the common configurations you may need to modify:

- **application.properties:** This file contains general application-level configurations, such as server port, service registration settings, and client settings.
