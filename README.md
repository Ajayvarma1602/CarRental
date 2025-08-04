# 🚗 CarRental - MERN Stack Full-Stack Web App

A modern and fully functional **Car Rental Application** built with the MERN stack (MongoDB, Express.js, React.js, Node.js). This project allows users to browse available cars, book rentals, and manage their bookings, while admins can manage the fleet with ease. The app is responsive, scalable, and integrates with cloud services like **MongoDB Atlas** and **ImageKit**.

---

## 🔗 Live Links

- 🌐 **Frontend (React/Vite)**: https://car-rental-ajays-projects-933b0779.vercel.app/
---

## 🧰 Tech Stack

### Frontend
- React.js (with Vite)
- React Router DOM
- Axios
- CSS Modules / Tailwind CSS (based on implementation)

### Backend
- Node.js
- Express.js
- MongoDB with Mongoose
- JWT Authentication
- bcrypt for password encryption
- dotenv, cors, helmet for config/security

---

## 🚀 Features

- 🔐 User Signup/Login with JWT auth
- 📆 Real-time car availability & booking system
- 📋 User dashboard for managing bookings
- ⚙️ Admin panel for car management (add/edit/delete)
- ☁️ Cloud-hosted images via ImageKit
- 📱 Fully responsive design for mobile & desktop

---

## 📁 Project Structure

```
CarRental/
├── client/            # React frontend
│   └── src/
│       ├── Components/
│       ├── Pages/
│       ├── assets/
│       └── App.jsx
├── server/            # Express backend
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── .env
│   └── index.js
├── package.json
└── README.md
```

---

## 🛠 How to Run This Project Locally

This project is a full-stack car rental system built with the MERN stack. To run it locally, follow the instructions below.

### ✅ Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/en/download/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register)
- [ImageKit.io](https://imagekit.io)

---

### 1️⃣ Setup Server

```bash
cd server
```

1. Create a `.env` file in the `server/` folder and add:

```
MONGO_URI=your_mongodb_connection_string
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
```

2. Install dependencies:

```bash
npm install
```

3. Start the backend server:

```bash
npm run server
```

---

### 2️⃣ Setup Client

```bash
cd client
```

1. Install frontend dependencies:

```bash
npm install
```

2. Start the React development server:

```bash
npm run dev
```

> 🔁 **Note:** Make sure the backend server is running before launching the frontend.

---

### 🌍 Deployment

This project is deployed using:
- **Frontend**: [Vercel](https://vercel.com/)
