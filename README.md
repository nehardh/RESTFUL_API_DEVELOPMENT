# Library System RESTful API

## Overview
This is a **RESTful API** for a **Library System** that allows managing books, authors, and users. It supports **CRUD operations** using **Node.js, Express, and MongoDB**.

## Features
- 📚 **Book Management**: Add, update, delete, and fetch books.
- 👤 **User Management**: Manage library users and their borrowing history.
- 📝 **CRUD Operations**: Fully functional endpoints for data management.
- 🔄 **RESTful Design**: Follows REST API best practices.
- ⚡ **Optimized Performance**: Uses indexing and efficient queries.

## Installation
```sh
# Clone the repository
git clone https://github.com/your-username/library-api.git

# Navigate to the project directory
cd library-api

# Install dependencies
npm install

# Create a .env file and add MongoDB connection string
MONGO_URI=your_mongodb_connection_string
PORT=5000

# Start the development server
npm run dev
```

## API Endpoints
### 📚 Books
| Method | Endpoint          | Description        |
|--------|------------------|--------------------|
| GET    | `/api/books`      | Get all books     |
| POST   | `/api/books`      | Add a new book    |
| GET    | `/api/books/:id`  | Get a book by ID  |
| PUT    | `/api/books/:id`  | Update a book     |
| DELETE | `/api/books/:id`  | Delete a book     |

### 👤 Users
| Method | Endpoint          | Description       |
|--------|------------------|-------------------|
| GET    | `/api/users`      | Get all users    |
| POST   | `/api/users`      | Add a new user   |
| GET    | `/api/users/:id`  | Get a user by ID |
| PUT    | `/api/users/:id`  | Update a user    |
| DELETE | `/api/users/:id`  | Delete a user    |

## Future Enhancements
- ✅ **Authentication**: Secure API using JWT authentication.
- 📃 **Swagger Documentation**: Implement API docs with Swagger.
- 🚀 **Performance Improvements**: Optimize database queries.

## License
MIT License

---

_Contributions are welcome! Feel free to fork this repo and submit a PR._ 🚀
