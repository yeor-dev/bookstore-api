# 📚 BookStore API

A RESTful API for managing a bookstore.  
Allows you to create, read, update, and delete books, authors, and categories.

## 🚀 Features

- CRUD operations for books, authors, and categories  
- Pagination and filtering for listing books  
- Validation of data inputs  
- RESTful API design with clear endpoints  
- JSON response format  
- Error handling with meaningful messages

## ⚙️ Technology Stack

- Node.js & Express.js (backend framework)  
- MongoDB & Mongoose (database & ODM)  
- Joi (data validation)  
- Postman (API testing)

## 📂 API Endpoints

| Method | Endpoint           | Description                       |
|--------|--------------------|---------------------------------|
| GET    | /api/books         | Get all books (with pagination) |
| GET    | /api/books/:id     | Get book details by ID           |
| POST   | /api/books         | Add a new book                  |
| PUT    | /api/books/:id     | Update a book by ID             |
| DELETE | /api/books/:id     | Delete a book by ID             |

### 📚 Book Endpoints

| Method | Endpoint           | Description                       |
|--------|--------------------|----------------------------------|
| GET    | /api/books         | Get all books (with pagination)  |
| GET    | /api/books/:id     | Get book details by ID           |
| POST   | /api/books         | Add a new book                   |
| PUT    | /api/books/:id     | Update a book by ID              |
| DELETE | /api/books/:id     | Delete a book by ID              |

### 👤 Author Endpoints

| Method | Endpoint              | Description                    |
|--------|-----------------------|--------------------------------|
| GET    | /api/authors          | Get all authors                |
| GET    | /api/authors/:id      | Get author by ID               |
| POST   | /api/authors          | Add a new author               |
| PUT    | /api/authors/:id      | Update author                  |
| DELETE | /api/authors/:id      | Delete author                  |

### 🏷️ Category Endpoints

| Method | Endpoint               | Description                   |
|--------|------------------------|-------------------------------|
| GET    | /api/categories        | Get all categories            |
| GET    | /api/categories/:id    | Get category by ID            |
| POST   | /api/categories        | Add a new category            |
| PUT    | /api/categories/:id    | Update category               |
| DELETE | /api/categories/:id    | Delete category               |

## 🔧 Installation & Running

1. Clone the repo  

```bash
git clone https://github.com/yeor-dev/bookstore-api.git
cd bookstore-api
npm install

2.Env file
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.xxxxxx.mongodb.net/bookstore

3.Start the server
npm start

📦 Repository

🔗 https://github.com/yeor-dev/bookstore-api

## 👨‍💻 Author

**Yeor Dev**  
GitHub: [@yeor-dev](https://github.com/yeor-dev)  
