# 🛒 E-Commerce Web Application (MERN Stack)

An advanced **E-Commerce Platform** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)** that allows users to browse products, add to cart, manage orders, and make secure payments. Designed with a responsive UI and complete authentication flow for both customers and admins.

---

## 🚀 Tech Stack

**Frontend:** React.js, Redux Toolkit, Axios, Bootstrap / Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Mongoose ODM)  
**Authentication:** JWT (JSON Web Token)  
**Cloud & Storage:** Cloudinary / AWS S3 (for product images)  
**Payment Gateway:** Razorpay / Stripe Integration  

---

## ✨ Key Features

### 🧑‍💻 User Features
- User Registration and Login (JWT Authentication)
- Profile Management and Order History
- Browse Products by Category, Price, or Search
- Add/Remove Items from Cart
- Checkout and Payment Integration
- Responsive and Modern UI

### 🛍️ Admin Features
- Admin Dashboard
- Add, Edit, Delete Products
- Manage Orders and Inventory
- View Customer Details and Transactions
- Secure Access with Admin Role

---

## 📂 Project Structure

```
E-Commerce/
├── client/                 # React frontend
├── server/                 # Node.js backend
├── assets/                 # Screenshots like login UI
├── README.md               # Project description file 
├── .gitignore              # Git ignored files config
```

## ⚙️ Installation and Setup

### 1️⃣ Clone the repository
- git clone [https://github.com/yourusername/ecommerce-mern.git](https://github.com/sujaytumu/e-commerce)
- cd ecommerce-mern
  
2️⃣ Setup Backend
- cd server
- npm install
- Create a .env file inside Backend_Nodejs/ and add:


    - PORT=5000
    - MONGO_URI=your_mongodb_connection_string
    - JWT_SECRET=your_jwt_secret
    - CLOUDINARY_API_KEY=your_cloudinary_key
    - CLOUDINARY_API_SECRET=your_cloudinary_secret
    - Start the backend server:  npm run dev
  
3️⃣ Setup Frontend
- cd client
- npm install
- npm run dev


💳 Payment Integration
- Integrated Stripe / Razorpay for secure online payments.
- Users can pay directly using debit/credit cards or UPI during checkout.

🔒 Authentication
- Implemented using JWT:
- Access Token for secure APIs
- Middleware protection for routes
- Role-based access (User/Admin)



🧪 API Endpoints (Sample)
- Method	Endpoint	Description
- POST	/api/users/register	Register new user
- POST	/api/users/login	Login user
- GET	/api/products	Fetch all products
- POST	/api/orders	Place new order
- GET	/api/orders/:id	Get order details

🌐 Deployment
Frontend: Vercel / Netlify
Backend: Render / Railway
Database: MongoDB Atlas


