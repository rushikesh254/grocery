# 🛒 Smart Grocery Management System

A full-stack grocery web application that allows sellers to manage products and orders, and customers to browse, search, and purchase groceries online. Built using the MERN stack with secure authentication and a responsive design.

## 🚀 Features

- Role-based access for sellers and customers
- Secure login and signup using JWT and Bcrypt
- Product management with image uploads
- Product search and category filtering
- Shopping cart and order history
- Mobile-friendly responsive UI
- RESTful APIs with proper error handling

## 🧰 Tech Stack

- Frontend: React.js, React Router, Axios, CSS3
- Backend: Node.js, Express.js
- Database: MongoDB, Mongoose
- Authentication: JWT, Bcrypt

## 📁 Folder Structure

/client – React frontend  
/backend – Node.js + Express backend

## 🛠️ Installation

1. Clone the repository  
   `git clone https://github.com/rushikesh254/grocery.git && cd grocery`

2. Install backend dependencies  
   `cd backend && npm install`

3. Install frontend dependencies  
   `cd ../client && npm install`

4. Create a `.env` file in the `backend` folder with the following:  
MONGO_URI=your_mongodb_connection_string JWT_SECRET=your_jwt_secret


5. Run the app  
In one terminal:  
`cd backend && npm run dev`  
In another terminal:  
`cd client && npm start`

## 📌 Future Improvements

- Payment gateway integration
- Admin dashboard
- Email notifications
- Unit testing

## 📬 Contact

Made with ❤️ by [Rushikesh](https://github.com/rushikesh254)
