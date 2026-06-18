# E-commerce Backend (Spring Boot)

A Spring Boot REST API for managing e-commerce products, built as a hands-on learning project to practice backend fundamentals — REST controllers, JPA, and file handling.

## What This Does

- Full CRUD operations for products (Create, Read, Update, Delete)
- Image upload and retrieval for each product
- In-memory H2 database for data storage
- Tested using Postman

## Tech Stack

- **Backend:** Java, Spring Boot, Spring Data JPA
- **Database:** H2 (in-memory)
- **Testing:** Postman

## Scope Note

This repository contains the **backend only**, which I built and understand fully. The frontend (React) was provided as part of a guided tutorial and is included separately to demonstrate the complete working application — it was not built by me.

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|--------------|
| GET | `/api/products` | Get all products |
| GET | `/api/products/{id}` | Get a single product by ID |
| POST | `/api/products` | Add a new product (with image) |
| PUT | `/api/products/{id}` | Update an existing product |
| DELETE | `/api/products/{id}` | Delete a product |
| GET | `/api/products/{id}/image` | Fetch product image |


## What I Learned

- Building REST APIs with Spring Boot
- Mapping entities and repositories with Spring Data JPA
- Handling file/image upload and storage in a Spring Boot application
- Testing APIs using Postman before connecting any frontend

## Status

Learning project — built while studying backend development with Spring Boot. Actively continuing to build more complex projects (authentication, security, deployment) as next steps.
