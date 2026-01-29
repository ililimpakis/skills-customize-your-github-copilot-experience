# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design, implement, and test RESTful APIs using the FastAPI framework in Python. By the end of this assignment, you will have created a simple API for managing a collection of resources (e.g., books, users, or tasks).

## 📝 Tasks

### 🛠️ Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and set up the basic structure for your API.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main application file (main.py)
- Set up a basic FastAPI app with a root endpoint (`/`) that returns a welcome message


### 🛠️ Implement CRUD Endpoints

#### Description
Add endpoints to create, read, update, and delete items in your resource collection (e.g., books).

#### Requirements
Completed program should:

- Implement POST, GET, PUT, and DELETE endpoints for your resource
- Use Pydantic models for request and response validation
- Store data in an in-memory list or dictionary


### 🛠️ Test Your API

#### Description
Test your API using HTTP requests (with curl, httpie, or a tool like Postman).

#### Requirements
Completed program should:

- Demonstrate example requests and responses for each endpoint
- Handle errors gracefully (e.g., resource not found)
- Include clear instructions for running and testing the API

