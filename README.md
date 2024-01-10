# Employee CRUD Application

This is a simple CRUD (Create, Read, Update, Delete) application for managing employee records. The project is built using Spring Boot and utilizes Spring Data JPA for data persistence.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Database Configuration](#database-configuration)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Contributing](#contributing)
- [Screenshots](#screenshots)


## Features

- Retrieve a list of all employees
- Retrieve details of a specific employee by ID
- Add a new employee
- Delete an employee by ID

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) installed
- Maven installed
- MySQL or another supported database running
- Better to use spring tool suite or eclipse for the project

## Database Configuration

1. Install and configure MySQL.

2. Create a database and a table for the application. Use the following SQL script in MySQL Workbench:


    ```sql
        CREATE DATABASE  mayur;

        USE mayur;

        CREATE TABLE employee (
            id BIGINT AUTO_INCREMENT PRIMARY KEY,
            first_name VARCHAR(255),
            last_name VARCHAR(255),
            designation VARCHAR(255)
        );



## Getting Started

1. Clone the repository:
    ```bash
       git clone https://github.com/Makarand41/Employees.git

2. Open src/main/java and run EmployeeCrudApplication.java


## Usage
Once the application is running, you can interact with it through the provided RESTful API. Use tools like Postman or curl to make HTTP requests to the defined endpoints.

## Endpoints
- GET /EmployeeCrud: Get a list of all employees
- GET /EmployeeCrud/{id}: Get details of a specific employee by ID
- POST /EmployeeCrud: Add a new employee
- Request Body: JSON representation of the new employee
- DELETE /EmployeeCrud/{id}: Delete an employee by ID


## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Screenshots


1. Post request in postman

![post](https://github.com/Makarand41/Employees/assets/90332486/fb80e860-72be-4231-8866-a91f58351f3a)


2. GET request in postman

![get](https://github.com/Makarand41/Employees/assets/90332486/43a2f916-6157-4fe6-9e86-673154959a76)


