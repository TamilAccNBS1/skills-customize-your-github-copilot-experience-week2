# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn to build a modern REST API using the FastAPI framework. You'll create endpoints to handle HTTP requests, work with request/response models, and implement data validation. This assignment teaches web development fundamentals and API design best practices.

## 📝 Tasks

### 🛠️ Create a Basic REST API

#### Description
Build a FastAPI application that exposes RESTful endpoints for managing a simple resource (such as a list of books, tasks, or products). Implement GET, POST, and basic data persistence.

#### Requirements
Completed program should:

- Create at least 3 endpoints (GET for listing, GET by id, and POST for creating items)
- Use Pydantic models for request/response validation
- Include proper HTTP status codes and error handling
- Support JSON request and response formats
- Store data in an in-memory list or database

### 🛠️ Add Advanced Features

#### Description
Enhance the API with additional functionality including update and delete operations, query parameters, and documentation.

#### Requirements
Completed program should:

- Implement PUT/PATCH and DELETE endpoints for updating and deleting resources
- Add query parameters for filtering or pagination
- Include proper input validation with meaningful error messages
- Use FastAPI's automatic API documentation (Swagger/OpenAPI)
- Demonstrate proper separation of concerns in code structure
