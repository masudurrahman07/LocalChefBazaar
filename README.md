# LocalChefBazaar – Role-Based Food Marketplace

## 📸 Screenshots

### 🏠 Home Page
![Home Page](./Screenshots/Homepage.png)


## 🔗 Live Website
https://local-chef-bazaar01.netlify.app/

## 📌 Project Overview
LocalChefBazaar is a full-stack food marketplace platform designed to connect local chefs with customers in a seamless and user-friendly way. The platform is built with a role-based system that provides different experiences for chefs, users, and admins. Chefs can create, update, and manage their meal listings, while users can browse available meals, place orders, and manage their order history. Admins have full control over the platform to monitor activities and manage users, meals, and orders.

The system includes secure authentication and authorization to ensure safe access for each role. It also implements full CRUD functionality for managing meals and orders efficiently. With a responsive and intuitive interface, LocalChefBazaar aims to create a smooth experience for both food providers and customers, making local food discovery and ordering more accessible and organized.

## 👥 User Roles & Features

### 👨‍🍳 Chef
- Create, update, and delete meals
- Manage listed food items
- View customer orders

### 👤 User
- Browse available meals
- Place food orders
- View order history
- Adds favourite meal

### 🛡️ Admin
- Manage users and chefs
- Control platform data
- Monitor meals and orders

## 🚀 Core Features
- Role-based authentication and authorization
- Secure JWT-based login system
- Full CRUD operations
- Meal creation and order management
- Protected routes for different user roles
- Responsive and intuitive UI

## 🛠️ Technologies Used

### Frontend
- React
- JavaScript
- Tailwind CSS

### Backend
- Node.js
- Express.js

### Database
- MongoDB

### Authentication & Security
- JWT (JSON Web Tokens)
- Protected API routes

## 📦 Major Dependencies
- express
- mongodb
- jsonwebtoken
- cors
- dotenv

## How to Run Locally
1. Clone the repository  
2. Run `npm install`  
3. Create a `.env` file with required variables (MongoDB URI, JWT secret)  
4. Start the server using `npm start`  
5. Run the client using `npm run dev`  
6. Open `http://localhost:5173` in your browser  

> Ensure the backend is running before starting the frontend.