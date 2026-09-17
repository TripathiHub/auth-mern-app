# MERN Authentication & Product Management App

A full-stack MERN application featuring user authentication, JWT-based protected routes, product management, and a basic shopping cart.

## 🚀 Tech Stack

### Frontend

* React
* Vite
* React Router
* React Toastify
* JavaScript
* CSS

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* bcrypt
* Joi
* CORS

## 📁 Project Structure

```text
auth-mern-app/
├── backend/
│   ├── controller/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── .env
│
└── .gitignore
```

## ✨ Features

* User signup and login
* Joi request validation
* Password hashing using bcrypt
* JWT authentication
* Protected frontend routes
* Protected backend API
* MongoDB database
* Product API
* Product listing
* Basic shopping cart
* Cart item count
* Cart total calculation
* Logout functionality
* Toast notifications

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/TripathiHub/auth-mern-app.git
cd auth-mern-app
```

## 🔧 Backend Setup

Move into the backend folder:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file inside the `backend` folder:

```env
MONGODB_URI=your_mongodb_connection_string
SECRET_KEY=your_secret_key
PORT=9000
```

Start the backend:

```bash
npm start
```

The backend will run on:

```text
http://localhost:9000
```

## 💻 Frontend Setup

Open another terminal and move into the frontend folder:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm run dev
```

The frontend will normally run on:

```text
http://localhost:5173
```

## 🔐 Environment Variables

Environment variables are required for sensitive information such as:

* MongoDB connection string
* JWT secret key
* Production API URL

`.env` files are excluded from Git using `.gitignore`.

**Never commit your `.env` file or expose your database credentials and secret keys publicly.**

## 🔄 Application Flow

```text
React Frontend
      │
      │ HTTP Requests
      ↓
Express.js Backend
      │
      ├── JWT Authentication
      ├── Joi Validation
      ├── bcrypt Password Hashing
      │
      ↓
MongoDB
```

## 🛒 Cart

The application currently implements a basic client-side shopping cart using React state.

It supports:

* Adding products to cart
* Displaying cart items
* Counting cart items
* Calculating the total price

Cart data is currently stored in React state and is not persisted after page refresh.

## 📌 Current Status

This project was created as a learning project to understand full-stack MERN development, authentication, REST APIs, database integration, and protected routes.

More advanced features can be added in future versions.

## 👨‍💻 Author

**Himanshu Tripathi**

GitHub: [TripathiHub](https://github.com/TripathiHub)
