# REST API with Node.js and SQLite

A simple RESTful API built using **Node.js**, **Express**, and **SQLite** that supports full CRUD operations on a collection of resources.  
The project also includes a client script to test API endpoints using HTTP requests.

---

## Overview

This project demonstrates how to:
- Build a REST API using Express.js
- Perform Create, Read, Update, and Delete (CRUD) operations
- Use SQLite as a lightweight database
- Test REST endpoints programmatically using Axios

The API runs locally and exposes endpoints for both collections and individual items.

---

## Technologies Used

- **Node.js**
- **Express.js**
- **SQLite3**
- **Axios** (for API testing)
- **Nodemon** (for development)


## Supported HTTP Operations

### Collection Endpoints
- `GET /api/` – Retrieve all items
- `POST /api/` – Create a new item
- `PUT /api/` – Update items
- `DELETE /api/` – Delete items

### Item Endpoints
- `GET /api/:id` – Retrieve a specific item
- `PUT /api/:id` – Update a specific item
- `DELETE /api/:id` – Delete a specific item


    
