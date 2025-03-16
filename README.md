# 📚 E-Learning Platform

An interactive e-learning platform that allows users to enroll in courses, take quizzes, and receive certifications. Built using **React.js**, **Node.js**, **Express.js**, and **MongoDB**.

Developed with the help of [**Abhay Singh**](https://github.com/abhay-invertis) and [**Aarush Saxena**](https://github.com/aarushx10).

## 🚀 Features
- 🏫 User roles: **Admin, Teacher, Student**
- 🎥 Video courses and interactive quizzes
- 💳 Razorpay payment integration
- 📊 Admin dashboard for course management
- 🔐 JWT-based authentication system
- 🚀 Deployed on **Vercel (Frontend)** and **Render/AWS (Backend)**

## 🛠️ Tech Stack
- **Frontend:** React.js, HTML, CSS, JavaScript
- **Backend:** Node.js, Express.js, MongoDB
- **Database:** MongoDB Atlas
- **Payment Gateway:** Razorpay
- **Version Control:** Git & GitHub

## 📂 Project Structure
```
e-Learning-Platform-main/
│── backend/     # Node.js & Express backend
│── frontend/    # React.js frontend
│── .env         # Environment variables (not included)
│── package.json # Dependencies
│── README.md    # Project documentation
```

## 🛠️ Installation
### 1️⃣ Clone the repository
```sh
git clone https://github.com/sakshamx25/e-learning-platform.git
cd e-learning-platform
```

### 2️⃣ Install dependencies
```sh
cd backend
npm install
cd ../frontend
npm install
```

## 🚀 Running the Project
### 1️⃣ Start the Backend Server
```sh
cd backend
npm run dev
```
🔹 Runs on **http://localhost:5000/**

### 2️⃣ Start the Frontend
```sh
cd frontend
npm run dev
```
🔹 Opens **http://localhost:5173/**

## 🔗 API Endpoints
| Method | Endpoint               | Description         |
|--------|------------------------|---------------------|
| POST   | `/api/admin/login`     | Admin login        |
| GET    | `/api/courses`         | Fetch courses      |
| POST   | `/api/payment`         | Process payment    |

## 🌎 Deployment
### **Frontend Deployment on Vercel**
1. Install Vercel CLI:
   ```sh
   npm install -g vercel
   ```
2. Deploy frontend:
   ```sh
   cd frontend
   vercel
   ```
3. Follow the Vercel setup instructions and deploy.

### **Backend Deployment on Render/AWS**
1. Create a Render account and select **Node.js** environment.
2. Connect your GitHub repository and select the **backend** folder.
3. Add environment variables (`MONGO_URI`, `PORT`, `JWT_SECRET`, etc.).
4. Deploy and get your backend URL.

## 📜 License
This project is licensed under the MIT License. Feel free to contribute! 🚀

