# Chat Application

A real-time chat application built with **React.js** and **Socket.io**, allowing users to join rooms and communicate instantly.

## About

This chat application was created purely for **practice** and to understand how **WebSockets** work. It enables users to enter a username, join a specific chat room, and exchange messages in real time. The application is built using React.js for the frontend and Socket.io for real-time communication.

## Features
- Join chat rooms with a username
- Real-time messaging using WebSockets
- Modern and clean UI with responsive design
- Lightweight and easy to deploy

## Installation

### Prerequisites
Make sure you have the following installed:
- Node.js (v14 or later)
- npm or yarn

### Steps to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/chat-application.git
   cd chat-application
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the server (ensure you have a backend running on port 4000):
   ```sh
   node server.js
   ```
4. Start the React frontend:
   ```sh
   npm start
   ```

## Project Structure
```
chat-application/
│── public/
│── src/
│   ├── components/
│   │   ├── Chat.js
│   ├── App.js
│   ├── index.js
│── server/
│   ├── server.js
│── package.json
│── README.md
```

## Technologies Used
- React.js (Frontend)
- Socket.io (WebSockets for real-time communication)
- Node.js & Express.js (Backend)
- CSS (Styling)

## How to Use
1. Enter a username.
2. Enter a room name.
3. Click **Join Room** to enter and start chatting.



