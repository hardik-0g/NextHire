# 🚀 NextHire – Full Stack Job Portal Platform

NextHire is a modern full-stack recruitment platform built using the MERN stack. It bridges the gap between job seekers and recruiters by providing a seamless hiring experience. Candidates can explore opportunities, apply for jobs, and manage applications, while recruiters can create companies, post jobs, and review applicants through a dedicated dashboard.

---

## 🌐 Live Demo

### Frontend (Live Application)

https://next-hire-umber.vercel.app/

### Backend API

https://nexthire-backend-e260.onrender.com

> **Important:** The backend is hosted on Render's free tier. If the backend has been inactive for some time, it may enter a sleep state. Before using the application, open the backend URL above and wait 30–60 seconds for the server to wake up. Once the message "Welcome to the server" appears, open the frontend application.

---

## ✨ Features

### 🔐 Authentication & Authorization

* Secure JWT-based authentication
* Role-based access control
* Protected routes for Recruiters and Candidates
* Persistent login sessions

### 👨‍🎓 Candidate Features

* Browse and search jobs
* View detailed job information
* Apply for jobs with a single click
* Track applied jobs from dashboard
* Manage personal profile

### 🧑‍💼 Recruiter Features

* Create and manage companies
* Upload company logos
* Post new job opportunities
* Update company information
* View applicants for each job
* Manage all job listings from a centralized dashboard

### 🎨 User Experience

* Fully responsive design
* Clean and modern UI
* Fast and intuitive navigation
* Real-time state management with Redux Toolkit

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Redux Toolkit
* React Router DOM
* Tailwind CSS
* shadcn/ui
* Axios

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* Cookie-Based Authentication

### Cloud Services

* Cloudinary (Image Storage)
* MongoDB Atlas (Database)
* Render (Backend Hosting)
* Vercel (Frontend Hosting)

---

## 📂 Project Structure

```bash
NextHire/
│
├── Client/
│   ├── src/
│   ├── components/
│   ├── redux/
│   ├── hooks/
│   └── utils/
│
├── Server/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   └── config/
│
└── README.md
```

---

## 🔒 Authentication Flow

1. User registers as Candidate or Recruiter
2. Credentials are validated securely
3. JWT token is generated
4. Protected routes enforce authorization
5. Recruiters manage companies, jobs, and applicants
6. Candidates browse and apply for jobs

---

## ⚙️ Getting Started

### 1. Clone Repository

```bash
git clone <repository-url>
cd NextHire
```

### 2. Configure Environment Variables

Create a `.env` file inside the `Server` directory:

```env
PORT=8000

MONGODB_URI=YOUR_MONGODB_URI

SECRET_KEY=YOUR_SECRET_KEY

CLOUDINARY_NAME=YOUR_CLOUDINARY_NAME
CLOUDINARY_API_KEY=YOUR_CLOUDINARY_API_KEY
CLOUDINARY_SECRET_KEY=YOUR_CLOUDINARY_SECRET_KEY

FRONTEND_URL=http://localhost:5173

NODE_ENV=development
```

Create a `.env` file inside the `Client` directory:

```env
VITE_BACKEND_URL=http://localhost:8000
```

---

### 3. Install Dependencies

Backend

```bash
cd Server
npm install
```

Frontend

```bash
cd Client
npm install
```

---

### 4. Run the Application

Start Backend

```bash
cd Server
npm run dev
```

Start Frontend

```bash
cd Client
npm run dev
```

---

## 🌐 Local Development URLs

Frontend

```text
http://localhost:5173
```

Backend

```text
http://localhost:8000
```

---

## 🚀 Deployment

### Frontend

Hosted on Vercel

https://next-hire-umber.vercel.app/

### Backend

Hosted on Render

https://nexthire-backend-e260.onrender.com

### Note for Recruiters and Reviewers

Since the backend is hosted on Render's free tier, the server may sleep after periods of inactivity. If the application appears slow on first load:

1. Open the backend URL.
2. Wait approximately 30–60 seconds.
3. Confirm the message "Welcome to the server".
4. Open the frontend application.

This only happens on the first request after inactivity.

---

## 🚀 Future Enhancements

* Saved Jobs Feature
* AI-Powered Job Recommendations
* Resume Parsing
* Email Notifications
* Interview Scheduling
* Real-Time Messaging
* Admin Dashboard
* Analytics & Reporting

---

## 👨‍💻 Developer

Hardik Jaiswal

B.Tech – Computer Science (AI & ML)

Passionate about Full Stack Development, Software Engineering, and Building Scalable Web Applications.

GitHub:
https://github.com/hardik-0g

LinkedIn:
https://www.linkedin.com/in/hardikjaiswal9580100/

---

## 🙌 Contributions

Contributions, feature requests, and suggestions are welcome.

Feel free to fork the repository, create a feature branch, and submit a pull request.
