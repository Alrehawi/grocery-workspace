# Grocery Workspace API

Enterprise-style RESTful API developed for grocery management system.
This project demonstrates backend API design, authentication, database integration, and secure enterprise API architecture.

---

## Overview

Grocery Workspace API is a backend service designed using modern REST API principles.
It provides endpoints for managing grocery items, users, and related business logic.

This project demonstrates professional backend development skills including:

* RESTful API design
* Secure authentication
* Database integration
* Enterprise-style backend architecture

---

## Technologies Used

* Laravel (PHP)
* REST API Architecture
* MySQL / SQL Database
* JWT Authentication (if applicable)
* Postman (API testing)
* Git and GitHub
* Linux-compatible backend environment

---

## API Features

* Structured REST API endpoints
* JSON request and response format
* Authentication and authorization
* Database-driven backend logic
* Error handling and validation
* Scalable backend design

---

## Example API Endpoint

### Get all products

Request:

GET /api/products

Response:

```json
[
  {
    "id": 1,
    "name": "Milk",
    "price": 2.5
  }
]
```

---

## Authentication Example

Request:

POST /api/login

Response:

```json
{
  "access_token": "your_token_here",
  "token_type": "Bearer"
}
```

---

## Project Structure

```
app/
routes/
database/
config/
```

---

## How to Run

Install dependencies:

```
composer install
```

Run server:

```
php artisan serve
```

API will be available at:

```
http://localhost:8000/api
```

---

## Purpose

This project was created to demonstrate enterprise-level backend and API development skills including:

* REST API design
* Secure backend development
* Database integration
* Enterprise architecture concepts

---

## Author

Ali Alrehawi
Senior Backend / API Developer
GitHub: https://github.com/Alrehawi
LinkedIn: https://www.linkedin.com/in/ali-alrehawi-4447961ab/
