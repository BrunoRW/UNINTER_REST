# Task Management API

## Overview
This project implements a RESTful API for managing tasks. The API allows users to create, retrieve, update, and delete tasks, each containing information such as the task name, due date, and responsible person.

## Objectives
- Implement a RESTful API for task management.
- Utilize Spring Boot for the application framework.
- Use MySQL as the relational database for data persistence.
- Follow REST standards for API design.

## Requirements

### Functional Requirements
1. Create a task with the following attributes:
   - Task Name
   - Due Date
   - Responsible Person
2. Retrieve all tasks.
3. Retrieve a specific task by ID.
4. Update an existing task.
5. Delete a task.

### Non-Functional Requirements
- The API must be developed using Java with Spring Boot.
- Use Spring Data JPA for data manipulation.
- Document the API using Postman or a similar tool.
- Ensure the API adheres to RESTful principles.

## Instructions for Implementation

1. **Project Setup:**
   - Create a Spring Boot project using Spring Initializr.
   - Add necessary dependencies: Spring Web, Spring Data JPA, MySQL Database.

2. **API Structure:**
   - **Model:** Create the `Task` entity with attributes: `id`, `name`, `dueDate`, and `responsible`.
   - **Repository:** Create `TaskRepository` interface extending `JpaRepository`.
   - **Controller:** Implement `TaskController` with REST endpoints.

3. **Data Persistence:**
   - Configure the database connection in `application.properties`.

4. **Testing and Documentation:**
   - Test the API using Postman to ensure all functionalities work as expected.

## Deliverables
- A filled activity notebook with the project link and screenshots of tests conducted in Postman, demonstrating each functionality of the API.

## Evaluation Criteria
- Ensure the project link is provided (GitHub or similar).
- Verify that the link is functional.
- Each test must include evidence (screenshot) showing the functionality.

## Conclusion
This API serves as a foundational tool for task management, providing essential functionalities while adhering to modern development practices.