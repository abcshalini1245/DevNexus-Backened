# 🚀 DevNexus Backend

<div align="center">

### Backend API for DevNexus — A Full Stack Developer Networking Platform

Secure • Scalable • Real-Time

![Node.js](https://img.shields.io/badge/Node.js-20+-green?logo=node.js)
![Express](https://img.shields.io/badge/Express.js-Backend-black?logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green?logo=mongodb)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Real--Time-black?logo=socket.io)
![AWS](https://img.shields.io/badge/AWS-EC2-orange?logo=amazonaws)
![License](https://img.shields.io/badge/License-MIT-green)

</div>

---

# 📖 About

DevNexus Backend powers the complete developer networking platform by providing secure authentication, profile management, connection requests, real-time messaging, email automation, and RESTful APIs.

The application is built with **Node.js**, **Express.js**, and **MongoDB**, following scalable backend practices and production-ready architecture.

---

# ✨ Features

## 🔐 Authentication & Security

- JWT Authentication
- HTTP-only Cookie Authentication
- User Registration
- User Login
- User Logout
- Password Hashing using bcrypt
- Forgot Password
- OTP Verification
- Password Reset
- Protected Routes
- Input Validation
- Error Handling Middleware

---

## 👤 User Management

- View Profile
- Edit Profile
- Upload Profile Picture
- Professional Information
- Social Links
- Skills
- Education
- Experience
- Company
- Location
- Profile Completion Support

---

## 🤝 Developer Networking

- Browse Developer Feed
- Send Connection Requests
- Ignore Developers
- Accept Requests
- Reject Requests
- View Connections
- Request Status Management

---

## 💬 Real-Time Chat

- Socket.IO Integration
- Instant Messaging
- Store Chat History
- Message Deletion
- Copy Message Support
- Reply Support (UI)
- Real-Time Updates

---

## 📧 Email Services

- Forgot Password OTP Emails
- Daily Notification Emails
- Connection Reminder Emails
- SMTP Integration

---

## ⏰ Scheduled Jobs

- Daily Email Notifications
- Automated Cron Scheduler
- Background Task Execution

---

## ☁️ Cloud Services

- MongoDB Atlas
- Cloudinary Image Upload
- AWS EC2 Deployment
- Nginx Reverse Proxy
- DuckDNS Custom Domain

---

# 🛠 Tech Stack

| Technology | Purpose |
|------------|---------|
| Node.js | Runtime |
| Express.js | REST API |
| MongoDB Atlas | Database |
| Mongoose | ODM |
| JWT | Authentication |
| bcrypt | Password Hashing |
| Socket.IO | Real-Time Communication |
| Nodemailer | Email Service |
| node-cron | Scheduled Jobs |
| Cloudinary | Image Storage |
| Multer | File Upload |
| Cookie Parser | Cookie Handling |
| CORS | Cross-Origin Requests |
| dotenv | Environment Variables |

---



## Authentication

- POST /signup
- POST /login
- POST /logout
- POST /forgot-password
- POST /verify-otp
- POST /reset-password

---

## User

- GET /profile/view
- PATCH /profile/edit
- POST /upload

---

## Feed

- GET /feed

---

## Connection Requests

- POST /request/send/:status/:userId
- POST /request/review/:status/:requestId
- GET /user/request/received

---

## Connections

- GET /user/connections

---

## Chat

- GET /chat/:targetUserId
- Real-Time Socket.IO Events

---

# 🔒 Security Features

- JWT Authentication
- Password Hashing
- Protected APIs
- Cookie Authentication
- Environment Variables
- Input Validation
- Error Handling Middleware

---

# ⚙️ Installation

Clone repository

```bash
git clone https://github.com/abcshalini1245/DevNexus-Backened
```

Install packages

```bash
npm install
```

Run server

```bash
npm run dev
```

---

## 🌍 Environment Variables

Create a `.env` file in the root directory and add the following:

```env
PORT=7777

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

FRONTEND_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password_or_app_password

BREVO_SMTP_HOST=smtp-relay.brevo.com
BREVO_SMTP_PORT=587
```



# 🚀 Deployment

The backend is deployed from scratch on **AWS EC2**.

Deployment includes:

- AWS EC2 Instance
- Ubuntu Server
- PM2 Process Manager
- Nginx Reverse Proxy
- DuckDNS Custom Domain
- MongoDB Atlas
- Cloudinary
- Environment Variables

---

# 🔄 System Workflow

```
Client
   │
   ▼
React Frontend
   │
Axios Requests
   │
   ▼
Express Server
   │
JWT Authentication
   │
   ▼
MongoDB Atlas
   │
Socket.IO
   │
Real-Time Chat
```

---

# 🚀 Upcoming Features

- Razorpay Premium Membership
- AI Chat Assistant
- Push Notifications
- Group Chat
- Voice Messages
- Video Calling
- File Sharing

---

# 📚 Learning

This backend was built while learning advanced backend development concepts from **Akshay Saini's Namaste Node.js** course. The APIs, deployment, real-time chat, email automation, authentication flow, and integrations were independently implemented and customized.

---

# 👩‍💻 Author

**Shalini Upadhyay**

M.Tech CSE • NIT Durgapur

GitHub

https://github.com/abcshalini1245

LinkedIn

https://www.linkedin.com/in/shalini-upadhyay11/

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.
