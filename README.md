# MERN Authentication Project

This is a full-stack **MERN Authentication System** with separate **frontend** (React + Vite) and **backend** (Node.js + Express + MongoDB).  
It supports user login, registration, password reset, and JWT-based authentication.

---

## 📂 Project Structure
Authentication/
│── backend/ # Express backend (API)
│ ├── Controllers/
│ ├── Middleware/
│ ├── Models/
│ ├── Routes/
│ ├── Utils/
│ ├── index.js
│ ├── package.json
│
│── frontend/ # React frontend (Vite + React)
│ ├── src/
│ ├── public/
│ ├── index.html
│ ├── vite.config.js
│ ├── package.json
│
│── .gitignore
│── README.md

🔐 Features

User registration & login

Password reset with OTP / email verification

JWT authentication & protected routes

Secure password hashing (bcrypt)

React frontend with authentication pages

🛠️ Tech Stack

Frontend: React, Vite, Axios, CSS

Backend: Node.js, Express, MongoDB, JWT, Bcrypt

Database: MongoDB (Mongoose)
