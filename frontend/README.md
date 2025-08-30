Vibbly – Real-time Chat & Video Calling Platform 📱💬🎥

🌍 Overview

Vibbly is a platform where people can practice conversations, make friends, and improve their language skills together.
It combines real-time chat, high-quality video calls, and community features in one place.

Built for hackathons, teams, and personal use, Vibbly makes online communication seamless, secure, and engaging with a modern responsive design.

🎯 Objectives

Seamless Communication: Real-time messaging & video calling in a single platform.

User-Centric Design: Clean, responsive, and intuitive UI.

Cross-Platform Accessibility: Works smoothly on web and mobile.

Privacy & Security: Secure authentication & data handling.

Scalability: Extensible architecture for future features like media sharing & group calls.

✨ Key Features
💬 Real-Time Chat

Instant 1-to-1 and group messaging

Online/offline status indicators

Typing indicators & message timestamps

Emoji & media sharing support

🎥 Video Calling

High-quality 1-to-1 video calls (powered by Stream API / WebRTC)

Call controls: mute/unmute, end call

Low-latency, real-time performance

🎨 User Experience

Modern responsive UI (React + Bootstrap)

Sidebar for quick navigation

Notifications for new messages & missed calls

Light & Dark theme support

🔐 Additional Features

Secure login/signup system (JWT Authentication)

Scalable backend with Socket.IO for real-time updates

MongoDB Atlas for reliable cloud-based data storage

Placeholder avatars & customizable profile pictures

🛠️ Tech Stack
Frontend

React.js (Hooks & Context API)

Bootstrap (responsive design)

Backend

Node.js

Express.js

Socket.IO (real-time chat & calls)

Video & Messaging

Stream API / WebRTC

Database

MongoDB Atlas

Others

JWT Authentication

Git & GitHub for version control

Deployment: Vercel (frontend) / Render / Heroku (backend)

🏗️ Architecture
🔹 Web Application Workflow

User signs up / logs in

Real-time socket connection is established

Messages are exchanged instantly via Socket.IO

Video call requests handled via Stream API / WebRTC

Data securely stored in MongoDB Atlas

🔹 Technical Flow

Frontend (React + Bootstrap) → Chat & video call UI
Backend (Node + Express) → REST APIs + WebSocket server
Database (MongoDB Atlas) → User, chat & call records
Stream API / WebRTC → Handles real-time video & media transfer

🔮 Future Enhancements

Group video calls with screen sharing

End-to-end encryption for chats & calls

Voice messages & message reactions

Gamification: badges, streaks, and points

AI-powered conversation partner for language practice

⚡ Installation & Setup
# Clone repository
git clone https://github.com/your-username/vibbly.git

# Navigate to project folder
cd vibbly

# Install dependencies (frontend + backend)
npm install

# Setup environment variables
# (Create a .env file in backend)
MONGO_URI=your-mongodb-atlas-uri
JWT_SECRET=your-secret-key
STREAM_API_KEY=your-stream-api-key
STREAM_API_SECRET=your-stream-api-secret

# Run backend server
npm run build

# Run frontend
npm start
