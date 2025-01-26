# Real-Time Chat Application

This is a real-time chat application built using the MERN (MongoDB, Express, React, Node.js) stack and Socket.IO. The app allows users to send and receive messages instantly in a clean, user-friendly interface.

---

## Features

- Real-time messaging with Socket.IO
- User authentication (register and login)
- Persistent chat history using MongoDB
- Responsive design
- Typing indicators
- Online/offline status updates
- Room-based chat support

---

## Tech Stack

### Frontend:
- React.js
- TailwindCSS (for styling)
- Axios (for API calls)

### Backend:
- Node.js
- Express.js
- MongoDB (via Mongoose)
- Socket.IO

---

## Prerequisites

Before running this application, ensure you have the following installed:

- Node.js
- MongoDB
- npm or yarn

---

## Installation

### Clone the Repository:
```bash
git clone https://github.com/nevilsonani/Chat-Application
cd realtime-chat-app
```

### Backend Setup:
1. Navigate to the backend folder:
   ```bash
   cd backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the backend directory and add the following:
   ```env
   PORT=5000
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   ```
4. Start the backend server:
   ```bash
   npm run dev
   ```

### Frontend Setup:
1. Navigate to the frontend folder:
   ```bash
   cd ../frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Create a `.env` file in the frontend directory and add the following:
   ```env
   REACT_APP_BACKEND_URL=http://localhost:5000
   ```
4. Start the frontend server:
   ```bash
   npm start
   ```

---

## Usage

1. Open your browser and navigate to `http://localhost:3000`.
2. Register a new user or log in with existing credentials.
3. Start chatting in real time!

---


---

## Key Scripts

### Backend Scripts:
- `npm run dev`: Starts the backend server in development mode.

### Frontend Scripts:
- `npm start`: Starts the frontend server in development mode.

---

## Dependencies

### Backend:
- Express
- Mongoose
- Socket.IO
- bcrypt
- dotenv
- jsonwebtoken

### Frontend:
- React
- Axios
- Socket.IO client
- TailwindCSS

---



