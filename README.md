# 💬 PulseChat

Connect instantly. Chat seamlessly. Communicate in real time.
PulseChat is a scalable real-time chat application built with modern web technologies, enabling seamless communication through low-latency messaging, secure authentication, and a highly customizable user experience. Designed with performance, scalability, and responsiveness in mind, PulseChat delivers an engaging messaging platform for modern users.

## 🌐 Live Demo

Try PulseChat live:

🔗 **Website:** [Visit PulseChat](https://pulsechat-harshmunjal.onrender.com/)

---

## ✨ Features

### 👤 Authentication & Security

* Secure User Authentication
* JWT-Based Authorization
* Protected Routes
* Password Encryption
* Session Management

### 💬 Real-Time Messaging

* Instant Message Delivery
* One-to-One Chat
* Real-Time Updates
* Online/Offline Status
* Typing Indicators
* Message Notifications

### 🎨 User Experience

* Responsive Design
* Modern Chat Interface
* Dark/Light Theme Support along with 20 different intuitive themes
* Mobile-Friendly Layout
* User Profile

### ⚡ Performance

* Low Latency Communication
* Optimized API Requests
* Efficient State Management
* Scalable Architecture

---

## 📸 Screenshots

* Login Page
  <img width="1907" height="902" alt="image" src="https://github.com/user-attachments/assets/fcab688e-24b7-48bc-be54-9301a60cc981" />
  
* Chat Dashboard
  <img width="1905" height="909" alt="Screenshot 2026-06-09 201219" src="https://github.com/user-attachments/assets/f4c25b25-d829-45c3-bd3f-b0bb7f3c8bd3" />

* User Profile
  <img width="1919" height="898" alt="Screenshot 2026-06-09 201307" src="https://github.com/user-attachments/assets/f5db317c-bd1a-487f-8872-c5d0556c1e1e" />

* Customisable Themes 
  <img width="1887" height="907" alt="Screenshot 2026-06-09 201355" src="https://github.com/user-attachments/assets/515184cc-420c-454b-ba3b-22ae45e44ac6" />

---

## 🏗️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Daisy UI
* Zustand

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Authentication

* JWT
* bcrypt

### Real-Time Communication

* Socket.IO

---

## 📂 Project Structure

```bash
PulseChat/
│
├── frontend/
│   ├── public/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── .env
├── README.md
└── package.json
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/harshmunjal20/PulseChat.git

cd PulseChat
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Frontend Dependencies

```bash
cd frontend
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file inside the backend directory:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLIENT_URL=http://localhost:3000
```

If using Socket.IO and cloud services:

```env
SOCKET_URL=your_socket_server_url
```

---

## 🚀 Running the Project

### Backend

```bash
npm run dev
```

### Frontend

```bash
npm start
```

---

## 📡 API Endpoints

### Authentication

```http
POST /api/auth/register
POST /api/auth/login
GET  /api/auth/me
```

### Users

```http
GET /api/users
GET /api/users/:id
```

### Messages

```http
GET  /api/messages/:conversationId
POST /api/messages
```

### Conversations

```http
GET  /api/conversations
POST /api/conversations
```

---

## 🔥 Key Highlights

* Real-Time Chat using Socket.IO
* Secure JWT Authentication
* Scalable MERN Architecture
* Responsive UI Across Devices
* Fast and Reliable Message Delivery
* Clean and Modern User Interface

---

## 🎯 Future Improvements

* Group Chats
* Voice Messages
* Video Calling
* Message Reactions
* Read Receipts
* File Sharing
* AI Chat Assistant
* End-to-End Encryption
* Push Notifications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository

```bash
git checkout -b feature/new-feature
```

2. Commit changes

```bash
git commit -m "Add new feature"
```

3. Push to branch

```bash
git push origin feature/new-feature
```

4. Open a Pull Request

---

## 📄 License

Licensed under the MIT License.

---

## 👨‍💻 Author

**Harsh Munjal**

* GitHub: [harshmunjal20 GitHub Profile](https://github.com/harshmunjal20?utm_source=chatgpt.com)
* Repository: [PulseChat Repository](https://github.com/harshmunjal20/PulseChat?utm_source=chatgpt.com)
