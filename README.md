# Spring Boot Banking API

A Spring Boot REST API for managing bank accounts, with CRUD operations (Create, Read, Update, Delete). The project uses SQL as the database and provides endpoints to add, retrieve, update, and delete accounts.

## Features

- **Create** an account
- **Read** account details
- **Update** an account
- **Delete** an account

## Technologies & Dependencies

- Java
- Spring Boot
- Spring Data JPA
- SQL (MySQL/PostgreSQL)
- RESTful API
- Maven


## Dependencies

Add the following dependencies to your `pom.xml` file:

```xml
<dependencies>
    <!-- Spring Boot Starter Web -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>

    <!-- Spring Boot Starter Data JPA -->
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>

    <!-- MySQL Driver -->
    <dependency>
        <groupId>mysql</groupId>
        <artifactId>mysql-connector-java</artifactId>
        <scope>runtime</scope>
    </dependency>

    <!-- Lombok (optional for reducing boilerplate code) -->
    <dependency>
        <groupId>org.projectlombok</groupId>
        <artifactId>lombok</artifactId>
        <version>1.18.20</version>
        <scope>provided</scope>
    </dependency>
</dependencies>

