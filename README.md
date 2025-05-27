# 💬 Real-Time Chat Application

> Project built during Full Stack Development Internship at CodTech IT Solutions
A real-time chat application that enables users to register, log in, and chat instantly with others. Built using modern web technologies, this project showcases the implementation of WebSocket-based communication, user authentication, and a clean UI for chatting.

---

## 🌟 Project Overview

This application allows multiple users to chat in real time. The backend uses **Node.js** and **Socket.IO** to maintain live connections, while the frontend uses **React** to create an interactive chat interface.

---

## 🔧 Features

- ✅ User signup and login
- 🔒 Secure authentication
- 💬 Real-time messaging with Socket.IO
- 👀 Online/offline user status
- ✍️ Typing indicator
- 📅 Timestamps on messages
- 🎨 Responsive and modern UI

---

## 🧰 Tech Stack

### ⚙️ Backend
- Node.js
- Express.js
- MongoDB + Mongoose
- Socket.IO
- JWT for Authentication

### 🎨 Frontend
- React.js
- React Router
- Axios
- Tailwind CSS

---

## 📁 Folder Structure
Chat-Application/
│
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ ├── utils/
│ ├── App.js
│ └── index.js
│
├── server/ # Node.js backend
│ ├── models/
│ ├── routes/
│ ├── controllers/
│ ├── server.js
│ └── config/
│
├── .gitignore
├── README.md
├── package.json

---

## 🚀 Getting Started

### Prerequisites

- Node.js
- MongoDB
- npm or yarn

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/uknation/Chat-Application.git
cd Chat-Application

2. Install dependencies for both client and server
cd server
npm install

cd ../client
npm install

3. Start the server and client
# From root directory
cd server
npm start

cd ../client
npm start

4. Visit http://localhost:3000
