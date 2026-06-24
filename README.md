# 🚀 Voice and Text Based System for Automated SQL Query Conversion

## 📌 Project Overview

This project enables users to interact with databases using voice or text input without writing SQL queries manually. The system converts user requests into SQL statements, executes them on the database and displays the results in a structured format.

## ✨ Key Features

- Voice and text-based query input
- Automatic SQL query generation
- Support for SELECT, INSERT, UPDATE and DELETE operations
- Support for JOINs, Nested Queries, Aggregate Functions, GROUP BY and HAVING clauses
- Multilingual support (English, Tamil, Hindi, Malayalam)
- Structured display of SQL queries and results
- User-friendly interface

## 🏗️ System Architecture

```text
User Input (Voice/Text)
        ↓
Frontend (React)
        ↓
Backend (Node.js & Express)
        ↓
Groq API
        ↓
SQLite Database
        ↓
Structured Result Output
```

## 🛠️ Technologies Used

- React.js
- Node.js
- Express.js
- SQL
- Groq API
- Web Speech API

## ⚙️ Working

- User enters a query through voice or text.
- Voice input is converted into text using the Web Speech API.
- The query is sent from the frontend to the backend.
- Groq API converts the natural language query into an SQL query.
- The generated SQL query is executed on the SQLite database.
- The database returns the result.
- The result and generated SQL query are displayed to the user.
