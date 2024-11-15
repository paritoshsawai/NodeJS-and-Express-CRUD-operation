# Online Book Review Application

## Overview
The **Online Book Review Application** is a server-side RESTful web service built using **Node.js** and **Express.js**. It allows users to manage books and reviews for an online bookstore. The application is designed to handle multiple users simultaneously, providing a smooth and efficient experience.

This project was developed as part of a backend development assignment, and it demonstrates core concepts such as CRUD operations, authentication, and asynchronous programming.

---

## Features

### General Users:
1. **Retrieve all books** available in the bookshop.
2. **Search for specific books** by:
   - ISBN
   - Author
   - Title
3. **Retrieve reviews/comments** for specific books.
4. **Register** as a new user.
5. **Login** to the application.

### Registered Users:
1. **Add a new review** for a book.
2. **Modify a book review** (only your own reviews).
3. **Delete a book review** (only your own reviews).

### Core Functionalities:
- **Simultaneous Access:** Supports multiple users managing books and reviews at the same time.
- **Authentication:** Implements session and JWT-based authentication to secure user operations.
- **Async Programming:** Uses Promises, Callbacks, and Async/Await to ensure efficient handling of API requests.

---

## API Endpoints

### General Endpoints:
1. **GET /books** - Retrieve a list of all books.
2. **GET /books/:isbn** - Get book details by ISBN.
3. **GET /books/author/:author** - Get books by author.
4. **GET /books/title/:title** - Get books by title.
5. **GET /reviews/:isbn** - Get reviews for a specific book.

### User Endpoints:
1. **POST /register** - Register a new user.
2. **POST /login** - Login as a registered user.

### Registered User Endpoints:
1. **POST /reviews/:isbn** - Add a new review for a book.
2. **PUT /reviews/:isbn** - Modify your review for a book.
3. **DELETE /reviews/:isbn** - Delete your review for a book.

---

## Project Structure

---

## Technologies Used
- **Node.js**
- **Express.js**
- **Axios**
- **JWT Authentication**
- **Session Management**
- **Async/Await and Promises**

---

## How to Run the Project

### Prerequisites:
- Node.js installed on your machine.
- A tool like Postman to test APIs.



