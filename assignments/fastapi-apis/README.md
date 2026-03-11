# 📘 Assignment: FastAPI REST APIs

## 🎯 Objective

Learn how to build RESTful APIs using the FastAPI framework in Python, including defining routes, handling requests and responses, and using data models.

## 📝 Tasks

### 🛠️ Setup FastAPI Application

#### Description
Create a basic FastAPI application and verify it runs.

#### Requirements
Completed project should:

- Install FastAPI and an ASGI server (e.g., uvicorn).
- Define a FastAPI app instance in a Python file.
- Include a simple root (`/`) GET endpoint that returns JSON message.
- Provide instructions or comments on how to start the server.

### 🛠️ Create CRUD Endpoints

#### Description
Implement Create, Read, Update, and Delete operations for a simple in-memory resource.

#### Requirements
Completed application should:

- Define a Pydantic model for the resource (e.g., `Item` with `id`, `name`, `price`).
- Implement endpoints:
  - `POST /items` to add a new item.
  - `GET /items/{item_id}` to retrieve an item.
  - `PUT /items/{item_id}` to update an item.
  - `DELETE /items/{item_id}` to remove an item.
- Use a Python dictionary or list as in-memory storage.
- Return appropriate HTTP status codes and JSON responses.
