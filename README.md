# 📚 Library Book Management System (MongoDB CRUD)

## 📌 Project Description
This project is a Library Book Management System developed to demonstrate
CRUD (Create, Read, Update, Delete) operations using MongoDB.

The application helps in managing book records such as title, author,
category, published year, and available copies.

---

## 🛠 Technologies Used
- Node.js
- Express.js
- MongoDB
- MongoDB Shell (mongosh)
- VS Code
- Postman
- Git & GitHub

---

## 🗄 Database Details
- Database Name: libraryDB
- Collection Name: books

### Schema Structure
---

## 🔄 CRUD Operations

### Create
- Insert new book records into MongoDB

### Read
- View all books
- View books by category
- View books published after 2018

### Update
- Increase / decrease available copies
- Change book category

### Delete
- Delete book only if availableCopies = 0

---

## ❗ Error Handling
- Prevent negative stock values
- Book not found handling
- Restrict deletion if copies are available
