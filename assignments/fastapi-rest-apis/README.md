# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Students will learn to build a simple RESTful API using the FastAPI framework in Python. This introduces modern web development concepts, request handling, and documentation generation.

## 📝 Tasks

### 🛠️  Set up FastAPI application

#### Description
Create a new FastAPI project that defines at least two endpoints for managing simple data (e.g. a list of users or tasks). Use Pydantic models for request and response validation.

#### Requirements
Completed project should:

- Install and import `fastapi` and `uvicorn`
- Define a main application instance
- Implement at least **GET** and **POST** endpoints under a common path (`/items` or `/users`)
- Use Pydantic models for request bodies and response schemas
- Return appropriate HTTP status codes
- Include inline documentation comments so the automatic Swagger UI works (run with `uvicorn`)

### 🛠️  Run and test the API

#### Description
Start the server locally and demonstrate that the endpoints work by sending sample requests.

#### Requirements

- Run the application using `uvicorn main:app --reload`
- Access the Swagger UI at `http://127.0.0.1:8000/docs` and show the endpoints
- Provide example `curl` commands or Python `requests` snippets to create and retrieve data

You may include a `main.py` starter file if desired to help students get started.