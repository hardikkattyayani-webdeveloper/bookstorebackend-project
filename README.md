# Book Store Backend API

A RESTful Book Store Backend API built using **Node.js**, **Express.js**, and **MongoDB**. This project provides CRUD operations for managing books in a bookstore database.

---

## 🚀 Features

* Add a new book
* Get all books
* Get book details by ID
* Update book information
* Delete a book
* MongoDB database integration
* RESTful API architecture

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB
* JavaScript

---

## 📂 Project Structure

```text
bookstorebackend-project/
│── route/
│── index.js
│── seedbook.js
│── package.json
│── .gitignore
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone <repository-url>
```

2. Install dependencies

```bash
npm install
```

3. Create a `.env` file and add your MongoDB connection string.

4. Start the server

```bash
npm start
```

---

## 📌 API Endpoints

| Method | Endpoint   | Description       |
| ------ | ---------- | ----------------- |
| GET    | /books     | Get all books     |
| GET    | /books/:id | Get a single book |
| POST   | /books     | Add a new book    |
| PUT    | /books/:id | Update a book     |
| DELETE | /books/:id | Delete a book     |

---

## 📖 Future Improvements

* User Authentication
* JWT Authorization
* Input Validation
* Pagination & Search
* Error Handling Middleware

---

## 👨‍💻 Author

**Hardik Kattyayani**
