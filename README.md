# E-Commerce Prototype
This is a full-stack e-commerce web application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). The project features a product management system, user authentication using JSON Web Tokens (JWT), image upload support with Multer, and a functional shopping cart. Built as a personal project to explore Full-Stack development.

## 🔧 Features
- 📦 Add, display, and delete products (with image uploads)

- 🛍️ Category-based product browsing

- 👤 User sign-up and login (JWT-based authentication)

- 🔐 Token-protected routes (e.g., for cart access)

- 🛒 Persistent shopping cart with MongoDB

- 🖼️ Image uploads stored locally via Multer

- 🧩 Organized structure (backend APIs, frontend, admin panel)

## 🛠️ Tech Stack
- Frontend: React.js

- Backend: Node.js, Express.js

- Database: MongoDB with Mongoose

- Authentication: JWT (with environment-based secret)

- File Uploads: Multer

- State Management: React hooks + local storage

## 📦 Installation

> ⚠️ Requires [Node.js](https://nodejs.org/) and [MongoDB](https://www.mongodb.com/) installed on your machine.

### 1. Clone the repo

```bash
git clone https://github.com/yourusername/e-commerce.git
cd e-commerce
```
### 2. Set up environment variables

Create a .env file in the server/ directory and add:

```bash
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```
### 3. Install dependencies
```bash
# Backend
npm install express
npm install jsonwebtoken
npm install mongoose
npm install multer
npm install cors

# Frontend
npm install

# Admin
npm install
```
### 📂 Folder Structure

```bash
e-commerce/
├── admin          # React admin
├── frontend/        # React frontend
├── backend/        # Express backend
├── .env           # Environment variables
└── README.md
```
