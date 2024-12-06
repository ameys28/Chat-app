###ChatEase###
A real-time chat application built using the MERN Stack (MongoDB, Express, React, and Node.js). This app allows authenticated users to chat in real time, showcasing features like online presence and chat history.

##Features##
User authentication with JWT-based session management.
Real-time messaging with WebSocket (Socket.io) integration.
Chat history persistence in MongoDB.
Online/offline user status indicators.
Timestamps for messages and an auto-scroll feature for the chat window.
Requirements
Ensure you have the following installed:

Node.js (v14 or above)
MongoDB (local or MongoDB Atlas)
Git
NPM or Yarn
Setup Instructions
1. Clone the Repository
bash
Copy code
git clone https://github.com/ameys28/Chat-app.git
cd Chat-app
2. Set Up the Backend
Navigate to the server directory:
bash
Copy code
cd server
Install dependencies:
bash
Copy code
npm install
Create a .env file in the server directory with the following values:
env
Copy code
PORT=5000
MONGO_URI=your-mongo-db-uri
JWT_SECRET=your-jwt-secret
Start the server:
bash
Copy code
npm start
3. Set Up the Frontend
Navigate to the client directory:
bash
Copy code
cd ../client
Install dependencies:
bash
Copy code
npm install
Create a .env file in the client directory with the following values:
env
Copy code
VITE_BACKEND_URL=http://localhost:5000
Start the React development server:
bash
Copy code
npm run dev
Running the Application
Start the backend server (server) and ensure MongoDB is running.
Start the frontend server (client) and access the app at http://localhost:5173.
Deployment
Backend hosted on Render: Backend URL
Frontend hosted on Netlify: Frontend URL
Usage Instructions
Sign Up: Create a new account with a username and password.
Log In: Authenticate to access chat functionality.
Chat:
Select a user from the online user list.
Send and receive messages in real time.
Log Out: End your session securely.
Technologies Used
Frontend: React, Tailwind CSS, Socket.io-client
Backend: Node.js, Express, Socket.io
Database: MongoDB (Atlas/local)
Hosting: Render (backend), Netlify (frontend)
