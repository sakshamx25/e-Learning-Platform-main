# 📚 E-Learning Platform

An interactive e-learning platform that allows users to enroll in courses, take quizzes, and receive certifications. Built using **React.js**, **Node.js**, **Express.js**, and **MongoDB**.
![Screenshot 2025-03-21 103356](https://github.com/user-attachments/assets/7f31c149-07ec-4c13-81b3-81623d1941c8)


Developed with the help of [**Abhay Singh**](https://github.com/abhay-invertis) and [**Aarush Saxena**](https://github.com/aarushx10).

## 🚀 Features
- 🏫 User roles: **Admin, Teacher, Student**
- ![Screenshot 2025-03-21 103436](https://github.com/user-attachments/assets/bcb72f3a-ffd2-4fad-9863-5b166d0430a5)

- 🎥 Video courses and interactive quizzes
- 💳 Razorpay payment integration
- 📊 Admin dashboard for course management
- 🔐 JWT-based authentication system
- 🚀 Deployed on **Vercel (Frontend)** and **Render/AWS (Backend)**
- ![Screenshot 2025-03-21 103417](https://github.com/user-attachments/assets/02594280-07d6-42f4-8423-71e9e575ea5e)


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

