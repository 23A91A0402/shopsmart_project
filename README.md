# ShopSmart: Your Digital Grocery Store Experience

ShopSmart is a MERN stack web application that allows users to browse grocery products, add them to a cart, and manage purchases.  
This project is built using **MongoDB, Express.js, React.js, and Node.js**.

---

## Features
- Browse and view grocery products
- Add items to cart
- Simple and clean UI
- REST API with MongoDB backend

---

## Project Structure
```
shopsmart/
 ├── backend/      # Express + MongoDB server
 └── frontend/     # React app
```

---

## How to Run the Project

### 1. Prerequisites
- Node.js (v16+ recommended)
- MongoDB (installed and running on your system)

### 2. Start MongoDB
Run MongoDB server:
```bash
mongod
```

### 3. Setup Backend
```bash
cd backend
npm install
node server.js
```
Server will run at `http://localhost:5000`.

### 4. Setup Frontend
Open a new terminal:
```bash
cd frontend
npm install
npm start
```
React app will run at `http://localhost:3000`.

---

## Notes
- Make sure MongoDB is running before starting the backend.
- You can add sample products using Postman (POST request to `/api/products`) or MongoDB Compass.

---

## Technologies Used
- **MongoDB** - Database
- **Express.js** - Backend framework
- **React.js** - Frontend library
- **Node.js** - Runtime environment

---

## Author
Created by [Your Name]
