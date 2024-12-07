# ChatEase

A real-time chat application built using the MERN Stack (MongoDB, Express, React, and Node.js). This application enables authenticated users to engage in live chat with features like online presence, chat history, and more.

## Features

- **User Registration and Login**: JWT-based authentication for secure login.
- **Secure Password Hashing**: Store user passwords securely in MongoDB.
- **Real-time Messaging**: WebSocket (Socket.io) support for real-time chat.
- **Chat History**: Persistence of messages in MongoDB for chat history.
- **Online/Offline Indicators**: Users' status (online/offline) shown in the app.

## Requirements

Before you start, ensure you have the following installed:

- **Node.js** (v14 or above)
- **MongoDB** (running locally or with a cloud service like MongoDB Atlas)
- **Git**
- **NPM** or **Yarn**

# Setup Instructions

## Prerequisites:
  Node.js and npm installed.
  
  MongoDB installed or access to a MongoDB cloud instance.
  
  Git installed.

## Steps to Run Locally:
1 Clone the Repository
```bash
  git clone https://github.com/ameys28/Chat-app.git
  cd Chat-app
```

## Set Up Environment Variables Create a .env file in the backend directory with the following:
```bash
  MONGO_URI=<your-mongodb-uri>
  JWT_SECRET=<your-jwt-secret>
  PORT=5000
```

## Install Backend Dependencies
```bash
  cd backend
  npm install
```

## Run the Backend Server
```bash
  npm run dev
```

## Install Frontend Dependencies
```bash
  cd frontend
  npm install
```

## Run the Frontend Application
```bash
  npm run dev
```

Access the Application Open http://localhost:5173 in your browser.

# Hosted URL
chatease-c94e.onrender.com/
