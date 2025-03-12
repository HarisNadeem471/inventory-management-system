# 🏪 Inventory Management System  

A **full-stack Inventory Management System** built with **Vue.js (Frontend), Node.js (Backend), MongoDB (Database), and XState (State Management Middleware)**.  
It provides **user authentication, inventory management, and a shopping interface** where customers can add items to the cart and generate receipts.  

---

## 🚀 **Features**  

### 🔑 **Authentication**  
✔ User **Signup & Login** with proper validation  
✔ **Password encryption & authentication** using JWT  

### 📦 **Inventory Dashboard**  
✔ **Add new items** with details (name, price, stock quantity)  
✔ **Search items** by name or category  
✔ **Update item details** (name, price, stock)  
✔ **Delete items** from the inventory  

### 🛒 **Shopping System**  
✔ **Search products** in the shop  
✔ **Add products to the cart** and set desired quantity  
✔ **Remove items** from the cart  
✔ **Checkout & generate a shopping receipt**  

### 🔄 **State Management with XState**  
✔ **XState Middleware** ensures smooth state transitions  
✔ **Finite State Machine (FSM)** for better UI/UX control  
✔ **Reduces unnecessary re-renders** and improves performance  

### 🔐 **User Management**  
✔ **Logout option** to securely end the session  

---

## 🛠️ **Tech Stack**  
- **Frontend:** Vue.js  
- **State Management:** XState  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT (JSON Web Tokens)  
- **Styling:** Tailwind CSS  
- **Deployment:** Vercel  

---

## 📂 **Project Structure**
/inventory-management-system 
│── inventory-management/ # Frontend (Vue.js) │── backend/ # Backend (Node.js, Express.js, MongoDB) 
│── README.md # Project documentation 
│── .gitignore # Ignored files


---

## 🚀 **Setup & Installation**  

### 1️⃣ **Clone the repository**  
```sh
git clone https://github.com/HarisNadeem471/inventory-management-system.git
cd inventory-management-system

2️⃣ Setup & Run Backend
cd backend
npm install  # Install backend dependencies
node server.js  # Start backend server
The backend runs at http://localhost:5000

3️⃣ Setup & Run Frontend
cd ../inventory-management
npm install  # Install frontend dependencies
npm run serve  # Start frontend application
The frontend runs at http://localhost:8080

📊 Database Schema (MongoDB)
The system stores data in MongoDB, and collections include:
✔ users → Stores registered users (username, email, password)
✔ products → Stores product details (name, price, stock, category)
