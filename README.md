Category Management Dashboard

A full-stack e-commerce dashboard for managing clothing categories. Users can sign up, log in, and view categories in a clean, responsive UI. Built with React, Node.js, and MongoDB.

---

## 🚀 Tech Stack

### 🖥️ Frontend
- React.js (Functional Components + Hooks)
- React Router DOM
- Axios
- Context API

### 🌐 Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JSON Web Token (JWT) for authentication
- Multer (for image upload)

### 🛠️ Tools
- Vercel/Netlify (Frontend Hosting)
- Render (Backend Hosting)
- MongoDB Atlas (Cloud Database)

---

## ✨ Features

### ✅ Authentication
- Sign Up & Login
- JWT-based Auth
- Session Persistence

### 📊 Dashboard
- View categories in grid layout
- Each card displays:
  - Category image
  - Category name
  - Item count

### ➕ Add Category (Optional)
- Add new categories via form
- Upload image (stored locally or on cloud)

### ✏️ Edit Category (Optional)
- Edit name, image, and item count

---

## 🛠️ How to Run Locally

### 🔧 Prerequisites
- Node.js and npm
- MongoDB (local or MongoDB Atlas)

---

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/category-dashboard.git
cd category-dashboard
2. Setup Backend
bash
Copy
Edit
cd server
npm install
Create a .env file inside /server with the following:

env
Copy
Edit
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Run the server:

bash
Copy
Edit
npm run dev
3. Setup Frontend
bash
Copy
Edit
cd client
npm install
Create a .env file inside /client with the following:

env
Copy
Edit
REACT_APP_API_URL=http://localhost:5000
Run the frontend:

bash
Copy
Edit
npm start
🌐 
