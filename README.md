# Book API

A simple RESTful API for managing a list of books using Express and MongoDB.

## Features

- Retrieve all books
- Add a new book
- Update an existing book
- Delete a book by its ID

## Technologies Used

- Node.js
- Express
- MongoDB
- Mongoose
- dotenv

## Installation

### Prerequisites

- Node.js (v12 or later)
- MongoDB (running locally or accessible via URI)

### Summary of Commands

- **Run the project**: 
  ```bash
  node index.js

### For Add a Book
curl -X POST http://localhost:3000/books -H "Content-Type: application/json" -d '{"title": "1984", "author": "George Orwell"}'
### For Update a Book
curl -X PUT http://localhost:3000/books/:id -H "Content-Type: application/json" -d '{"title": "Animal Farm", "author": "George Orwell"}'
### For Delete a Book
curl -X DELETE http://localhost:3000/books/:id



