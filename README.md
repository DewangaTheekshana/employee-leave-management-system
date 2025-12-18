# Employee Leave Management System (MERN Stack)

This is a backend-focused Employee Leave Management System built using the MERN stack.
Employees can apply for leave, and admins can approve or reject leave requests.

---

## 🛠 Tech Stack

### Backend
- Node.js
- Express.js
- MongoDB
- JWT Authentication
- bcrypt

### Frontend
- React.js
- Bootstrap

---

## 📂 Project Structure

employee-leave-system/
│
├── server/
├── client/
└── README.md

---

## 🔐 Authentication & Roles

- **Admin**
  - View all leave requests
  - Approve or reject leave requests
  - Register new employees

- **Employee**
  - Apply for leave
  - View own leave history

---

## ⚙️ Backend Setup

1. Navigate to backend folder
```bash
cd server

2. Install dependencies

npm install


Create .env file

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key


Start backend server

npx nodemon server.js
