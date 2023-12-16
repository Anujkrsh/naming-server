# Naming Server Microservice

The Naming Server Microservice is a Java-based Eureka Server developed with Spring Boot and Spring Cloud. It is responsible for service registration and discovery in a microservices architecture.

## Table of Contents

- [Overview](#overview)
- [Configuration](#configuration)
- [Prerequisites](#prerequisites)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The Naming Server Microservice serves as the Eureka Server, allowing microservices to register and discover each other dynamically. It provides a centralized registry for managing service instances in a distributed system.

## Configuration

### Application Properties

Configure the application properties based on your environment. Modify the `application.properties` or `application.yml` file located in `src/main/resources/`.

   ```yaml
   # application.properties or application.yml

   spring.application.name=naming-server
   server.port=8761

   eureka.client.register-with-eureka=false
   eureka.client.fetch-registry=false
   ```
Adjust the properties such as server.port based on your specific requirements


## Prerequisites
Before running the Naming Server Microservice, ensure you have the following installed:

- Java Development Kit (JDK)
- Integrated Development Environment (IDE) such as IntelliJ or Eclipse
- Spring Boot

## Setup

1. Clone Repository
   git clone https://github.com/your-username/naming-server.git
2. Open the project in your preferred IDE.

3. Review and update the application properties:
src/main/resources/application.properties or src/main/resources/application.yml
4. Ensure Maven dependencies and plugins are configured:

Check the Maven POM file.

## Usage 

The Naming Server Microservice starts on port 8761 by default. After starting the microservice, you can access the Eureka Server dashboard at http://localhost:8761 in your web browser.

