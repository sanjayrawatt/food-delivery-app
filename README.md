# 🍔 Food Delivery App

A full-stack food delivery web application built using the **MERN stack (MongoDB, Express.js, React.js, Node.js)**. Users can register, log in, browse the menu, add items to cart, and place orders.

---

## 🚀 Features

- 🔐 User Authentication (Register/Login)
- 🍽️ Browse and view restaurant menu
- 🛒 Add to Cart & Checkout flow
- 📦 Order placement (Upcoming)
- 📊 Admin panel for managing orders (Planned)

---

## 🧑‍💻 Tech Stack

| Frontend        | Backend          | Database   |
|----------------|------------------|------------|
| React (with Router) | Node.js & Express | MongoDB (Atlas) |
| Axios          | REST APIs        | Mongoose   |
| CSS            | JWT Auth         |            |

---

## 🗂️ Project Structure

food-delivery-app/
├── backend/ # Express server, MongoDB models, routes
│ └── routes/
│ └── controllers/
│ └── models/
│ └── config/
├── frontend/ # React app with pages & components
│ └── src/
│ ├── pages/
│ ├── components/
│ └── App.js
└── README.md



---

## 🛠️ Getting Started

### 🔧 Prerequisites

- Node.js (v18+)
- MongoDB Atlas account
- Git

### 🔹 Clone the Repo

```bash
git clone https://github.com/sanjayrawatt/food-delivery-app.git
cd food-delivery-app
cd backend
npm install
touch .env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
node server.js
cd ../frontend
npm install
npm start


---

### ✅ Save It

1. Create a file called `README.md` inside your `food-delivery-app/` folder.
2. Paste the above content.
3. Then commit and push:

```bash
git add README.md
git commit -m "📝 Add project README"
git push

