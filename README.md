# Real-Time Chat Application

This project is a real-time chat application built with a React frontend and a Node.js backend using Express and Socket.io. It allows users to join a chat room and exchange messages in real-time.

## Technologies Used

- Frontend: React, React Router
- Backend: Node.js, Express, Socket.io
- Other: CORS for cross-origin resource sharing

## Project Structure

- `cchat/`: React frontend application
- `server/`: Node.js backend server

## Setup Instructions

### Backend

1. Navigate to the `server` directory:
   ```bash
   cd server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   npm start
   ```
   The server will run on port 4500 by default.

### Frontend

1. Navigate to the `cchat` directory:
   ```bash
   cd cchat
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the React development server:
   ```bash
   npm start
   ```
   The frontend will typically run on port 3000.

## Usage

- Open the frontend application in your browser (usually at `http://localhost:3000`).
- On the join page, enter your username to join the chat.
- Send and receive messages in real-time with other connected users.

## License

This project is licensed under the ISC License.
