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

*1. Navigate to backend folder*
```bash
cd server
```

*2. Install dependencies*
```bash
npm install
```

*3. Create .env file*
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

*4. Start backend server*
```bash
npx nodemon server.js
```

👤 *Admin Account Setup*

*Option 1*: Run Admin Seeder
```bash
node seed/adminSeeder.js
```

👥 *Employee Test Accounts*

*Option 1*: Run Employee Seeder
```bash
node seed/employeeSeeder.js
```

*Option 2*: *You Can add Employee Admin Dashboard*

---

## 🌐 Frontend Setup

*1. Navigate to client folder*
```bash
cd client
```

*2. Install dependencies*
```bash
npm install
```

*3. Start frontend*
```bash
npm start
```
---

## 🧪 API Testing

All APIs can be tested using Postman.
Protected routes require JWT token in Authorization header.

---

## ✅ Features

• JWT Authentication
• Role-based Authorization
• Leave request management
• Admin approval/rejection
• Audit logging (bonus)
• Employee registration by admin

---

## 📌 Notes

• .env file is not committed for security reasons.
• This project focuses mainly on backend logic as per assignment requirements.

---

## 👨‍💻 Author

• *Dewanga Theekshana Akash*

• GitHub: https://github.com/DewangaTheekshana
