# Spring Boot CRUD with PostgreSQL

This project is a simple Spring Boot application that implements a **CRUD** (Create, Read, Update, Delete) for a `Customer` entity using **Spring Data JPA** and **PostgreSQL** as the database. It is built with **Maven** for dependency management.

## Features

- **Create** a new customer
- **Read** customer details
- **Update** customer information
- **Delete** a customer

## Technologies Used

- **Spring Boot**: Framework for building Java applications
- **PostgreSQL**: Relational database used for storing customer data
- **Spring Data JPA**: Simplifies the implementation of JPA-based repositories
- **Maven**: Build and dependency management tool

## Prerequisites

Before running the application, ensure you have the following installed:

- **Java 17** or higher
- **PostgreSQL** database
- **Maven** for building the application

## Getting Started

### 1. Clone the repository

```bash
git clone https://https://github.com/OmarDIOP0/customer-crud-spring-boot.git
cd customer-crud-spring-boot
```

### 2. Install maven

```bash	
   mvn clean install
```	

### 3. Run docker composer

```bash	
   docker composer up -d
```

### 4. Run Spring Boot Application

```bash	
   mvn spring-boot:run
```

