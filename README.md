🌎 Lee esto en:[Español](README.es.md)

# 📦 Inventory Management System

A complete inventory management system composed of a **REST API backend** and a **web frontend**, designed as a professional fullstack project for portfolio purposes.

This system allows user authentication, product management, stock control, input/output stock movement tracking, and data visualization through a modern user interface.

---

## 🧱 System Architecture

The project is divided into two independent applications:

### 🔙 Backend – Inventory API
REST API built with Node.js and MongoDB.

👉 [Go to Backend Repository](./inventory-backend)

**Responsibilities:**
- JWT-based authentication
- User and role management
- Products CRUD
- Stock control
- Stock movement tracking
- API documentation with Swagger

---

### 🖥️ Frontend – Inventory Frontend
Web application built with React + Vite.

👉 [Go to Frontend Repository](./inventory-frontend)

**Responsibilities:**
- User login
- REST API consumption
- Products visualization
- Stock movement registration
- Low stock visual alerts
- JWT session handling

---

## 📂 Project Structure

```bash
inventory-system/
├── inventory-backend/
│   ├── README.md
│   └── README.es.md
├── inventory-frontend/
│   ├── README.md
│   └── README.es.md
├── README.md
└── README.es.md
```

🚀 Technologies Used
Backend

Node.js

Express.js

MongoDB + Mongoose

JWT

Swagger (OpenAPI)

bcryptjs

Frontend

React

Vite

JavaScript (ES6+)

Axios

CSS

JWT Authentication

🎯 Project Purpose

This project was developed as professional practice, focused on:

Clean architecture

Separation of concerns

JWT-based security

Real REST API consumption

Scalability

Best development practices

🧑‍💻 Author

Erik Eduardo Escobar Farías

Fullstack project developed for professional and portfolio purposes, simulating a real-world inventory system used in cafés, retail stores, and small warehouses.