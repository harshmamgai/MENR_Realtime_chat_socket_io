# Real-Time Chat Application

This is a real-time chat application built using the MERN stack (MongoDB, Express.js, React, Node.js) with Socket.io for real-time communication. The project uses React Router for navigation and the Context API for state management.

## Features

- **Real-Time Communication:** Utilizes Socket.io for instant messaging and updates.
- **User Authentication:** Allows users to sign up, log in, and track their conversations.
- **React Router:** Implements client-side routing for a seamless single-page application experience.
- **Context API:** Manages global state, providing easy access to data throughout the app.

## Technologies Used

- **Frontend:**
  - React
  - React Router
  - Context API

- **Backend:**
  - Node.js with Express.js
  - Socket.io for real-time features
  - MongoDB for data storage

## Installation

1. Clone the repository:
   ```bash
   https://github.com/harshmamgai/MENR_Realtime_chat_socket_io.git
   cd real-time-chat-app

## Install dependencies for both the server and client:

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

# Configure Environment Variables:

Create a .env file in the server directory and set your MongoDB URI and other necessary variables.
Run the Application:
# Run the server
cd server
npm start

# Run the client
cd ../client
npm start

# Usage
Open your browser and go to http://localhost:3000 to access the chat application.
Sign up, log in, and start real-time conversations.
