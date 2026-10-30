# 📚 Library Book Management System

A clean, browser-based **Library Book Management System** built with pure HTML, CSS, and JavaScript — no server or external libraries needed.

## 📋 Features

- 📖 **Add Books** — Register books with a unique Book ID and title
- 🎓 **Register Students** — Add students with a unique Student ID and name
- 📤 **Issue Books** — Issue an available book to a registered student
- 📥 **Return Books** — Return an issued book back to the library
- 📊 **Live Status Tables** — Book availability status, student list, and issued books update in real time

## 🚀 Getting Started

No installation needed. Just open in any modern browser:

```
LIB/index.html
```

## 🛠️ Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Structure & Layout |
| CSS3 | Styling |
| JavaScript (Vanilla) | Business Logic & DOM Manipulation |

## 📁 Project Structure

```
LIB/
└── index.html    # All-in-one HTML file (HTML + CSS + JS)
```

## 💡 How to Use

1. **Add a Book** — Enter Book ID and Book Name, click **Add Book**
2. **Add a Student** — Enter Student ID and Student Name, click **Add Student**
3. **Issue a Book** — Select a book and a student from the dropdowns, click **Issue**
4. **Return a Book** — Enter the Book ID in the return field, click **Return**

## ✅ Validations

- Book ID and Student ID must be unique
- A book already issued cannot be issued again until returned
- All fields (ID and Name) are required for adding books/students
- Return requires an actual Book ID that is currently issued

## 📊 Book Status

| Status | Meaning |
|--------|---------|
| ✅ Available | Book is in the library and can be issued |
| ❌ Issued | Book is currently borrowed by a student |

## 📌 Notes

- Data is stored in-memory (JavaScript arrays) and resets on page refresh
- No external dependencies or internet connection required
