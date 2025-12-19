# Employee Spring Boot CRUD Application

## Description
A simple Spring Boot REST API for managing employee data using CRUD operations.

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL / H2
- Postman

## Features
- Create employee
- Get employee by ID
- Get all employees
- Update employee details
- Delete employee
- Fetch employees by job
- Fetch employees by salary range

## API Endpoints
- POST /save
- GET /getByid?id={id}
- GET /fetchAll
- PUT /update/{id}
- DELETE /delete/{id}
- GET /fetchByJob?job={job}
- GET /fetchBysal?st={start}&end={end}

## How to Run
1. Run `EmployeeSpringbootApplication`
2. Server starts on port 8080
3. Test APIs using Postman
