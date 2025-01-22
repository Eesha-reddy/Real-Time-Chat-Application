## Realtime Chat Application

This project is a real-time messaging platform built with the MERN stack and Socket.io. It provides a responsive and interactive user experience, leveraging modern web technologies.

---

## Highlights

- Built with the MERN stack (MongoDB, Express.js, React.js, Node.js).
- Implements real-time communication using Socket.io.
- Secure user authentication and authorization with JWT.
- Responsive UI designed with TailwindCSS and DaisyUI.
- State management using Zustand for scalability.
---

## Tech Stack

- Frontend: React.js, TailwindCSS, DaisyUI
- Backend: Node.js, Express.js
- Database: MongoDB
- Real-Time Communication: Socket.io
- State Management: Zustand

---

## Getting Started

### Prerequisites

Ensure you have the following installed:

- Node.js
- MongoDB

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/realtime-chat-app.git
   cd realtime-chat-app
   ```

2. **Install Dependencies**

   - Backend:
     ```bash
     cd backend
     npm install
     ```
   - Frontend:
     ```bash
     cd ../frontend
     npm install
     ```

3. **Configure Environment Variables**
   Create a `.env` file in the `backend` directory with the following:

   ```env
   MONGODB_URI=your_mongodb_connection_string
   PORT=5001
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   NODE_ENV=development
   ```

4. **Run the Application**

   - Start Backend:
     ```bash
     cd backend
     npm start
     ```
   - Start Frontend:
     ```bash
     cd ../frontend
     npm start
     ```

Access the app at `http://localhost:3000`.

---
