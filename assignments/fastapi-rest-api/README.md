# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn to build REST APIs using the FastAPI framework in Python. You'll create endpoints that handle HTTP requests and responses, implement basic CRUD operations, and understand how to structure a web API.

## 📝 Tasks

### 🛠️ Setting Up FastAPI Application

#### Description
Create a basic FastAPI application with a root endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Import FastAPI and create an app instance
- Create a GET endpoint at "/" that returns a JSON response with a welcome message
- Run the server and verify the endpoint works

### 🛠️ Implementing CRUD Endpoints

#### Description
Add endpoints for managing a simple resource (e.g., items or tasks) with full CRUD operations.

#### Requirements
Completed program should:

- Create a data model for the resource (e.g., Item with id, name, description)
- Implement GET /items to retrieve all items
- Implement POST /items to create a new item
- Implement GET /items/{item_id} to retrieve a specific item
- Implement PUT /items/{item_id} to update an item
- Implement DELETE /items/{item_id} to delete an item
- Use appropriate HTTP status codes and response models