# 💬 Chatify - Real-Time Chat Application

Chatify is a full-stack real-time chat application built with the MERN stack. It enables users to communicate instantly through one-to-one messaging, securely authenticate, upload images, and receive welcome emails upon registration. The application provides a modern and responsive user experience powered by Socket.IO and React.

---

## 🚀 Features

- 🔐 Secure JWT Authentication
- 💬 Real-Time Messaging using Socket.IO
- 🟢 Online & Offline User Presence
- 🖼️ Image Sharing with Cloudinary
- 📨 Welcome Emails using Resend
- 🔒 Password Hashing with bcrypt
- ⚡ RESTful API built with Express.js
- 🗄️ MongoDB Database with Mongoose
- 🛡️ API Security & Rate Limiting using Arcjet
- 🎨 Responsive UI with React, Tailwind CSS & DaisyUI
- 📦 Global State Management using Zustand

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Tailwind CSS
- DaisyUI
- Zustand
- Axios
- Socket.IO Client

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- Socket.IO
- Cloudinary
- Resend
- Arcjet
- bcryptjs

---

## 📁 Project Structure

```
Chatify
│
├── backend
│   ├── src
│   ├── package.json
│   └── .env
│
├── frontend
│   ├── src
│   ├── public
│   └── package.json
│
└── README.md
```

---

## ⚙️ Environment Variables

Create a `.env` file inside the **backend** folder.

```env
PORT=3000

MONGO_URI=your_mongodb_connection_string

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_address
EMAIL_FROM_NAME=Chatify

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```
## 🔮 Future Improvements

- 👥 Group Chat Support
- 😊 Emoji Picker
- 📞 Audio & Video Calling
- ✔️ Read Receipts
- ✍️ Message Editing & Deletion
- 🌙 Dark & Light Theme Toggle
- 🔍 User Search & Chat Filtering
- 📱 Progressive Web App (PWA)

---

## 👨‍💻 Developer

**Yuvraj Singh**

B.Tech Computer Science Engineering

GitHub: https://github.com/Yuvrajsingh1256

---