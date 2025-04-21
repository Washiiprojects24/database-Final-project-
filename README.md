# database-Final-project-
# 📦 Full-Stack MySQL Project: Library Management System & Contact Book API

## 🚀 Project Overview

This repository contains **two complete MySQL-based applications**:

1. **📚 Library Management System**  
   A fully relational MySQL database for managing books, authors, members, and book loans.

2. **📇 Contact Book CRUD API**  
   A RESTful API using **FastAPI + MySQL** to manage contact details and addresses with full CRUD functionality.

---

## 🛠️ Technologies Used

- **MySQL** – Database engine
- **FastAPI** – Python web framework for the API
- **Uvicorn** – ASGI server for running FastAPI
- **MySQL Connector** – Python connector for MySQL

---

## 📁 Project Structure
---

## 📘 1. Library Management System (MySQL)

### 🔍 Description

A relational database to manage books, authors, members, and loan records in a library. It includes proper normalization, primary/foreign keys, and relationship constraints.

### 📥 How to Set Up

1. Open MySQL or your preferred SQL client (e.g., MySQL Workbench).
2. Run the script `library.sql` to create the database, tables, and insert sample data.

### 📊 ERD Diagram

![Library ERD](./erd.png)
*You can also generate one using [dbdiagram.io](https://dbdiagram.io), [drawSQL](https://drawsql.app), or [MySQL Workbench].*
--

## 📇 2. Contact Book CRUD API (FastAPI + MySQL)

### 🔍 Description

A simple API that allows you to **Create**, **Read**, **Update**, and **Delete** contact records and associated addresses.

### ⚙️ Tech Stack

- **FastAPI**
- **MySQL**
- **Pydantic**
- **MySQL Connector (Python)**

### 📥 How to Set Up

#### 🧱 Step 1: Set up MySQL database

1. Run `contact_schema.sql` in your SQL client.
2. Make sure MySQL is running locally (`localhost:3306` by default).

#### 🐍 Step 2: Install dependencies

```bash
pip install fastapi uvicorn mysql-connector-python
