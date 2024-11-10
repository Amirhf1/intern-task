# Backend Intern Task: Library Management API

## Overview

This task is designed to assess your skills in developing a RESTful API using Laravel. You will be creating a simple library management system to handle basic operations related to books.

## Objectives

- Build a comprehensive understanding of routing, controllers, and model interactions in Laravel.
- Implement middleware for request logging.
- Write unit tests to ensure the functionality of the API.

## Requirements

### Data Model

Create a `Book` model with the following attributes:
- `title`: string
- `author`: string
- `published_date`: date
- `genre`: string

### Routes and Controllers

Develop the following endpoints:
- `POST /books`: Add a new book to the library.
- `GET /books`: Retrieve a list of all books.
- `GET /books/{id}`: Retrieve a specific book by its ID.
- `PUT /books/{id}`: Update the details of a specific book.
- `DELETE /books/{id}`: Remove a book from the library.

### Middleware

Implement a simple middleware that logs all incoming requests to the API. This should include the time of request, the requested endpoint, and the method used.

### Unit Testing

Write tests for each of the endpoints to ensure they are functioning as expected:
- Test that each endpoint returns the correct status codes.
- Test that the `GET`, `PUT`, and `DELETE` endpoints handle non-existent book IDs appropriately.
- Test the output of `GET /books` to ensure it returns a correct data structure.

## Submission Guidelines

- Your code should be submitted as a merge request to the designated repository with all changes clearly commented and documented.
- Ensure all your tests pass before submitting your code.
- Include a brief report (1-2 pages) detailing your development process and any challenges you faced.

## Evaluation Criteria

- Code cleanliness and organization.
- Proper use of Laravel features (Eloquent, routing, middleware).
- Completeness of the implemented features.
- Quality and coverage of unit tests.
