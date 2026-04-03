# 💬 WebSocket Chat Application

A real-time chat application built using **WebSockets**, enabling instant communication between multiple users.
This project was developed to understand low-level real-time communication without relying heavily on frameworks.

---

## 🚀 Features

* 💬 Real-time messaging using WebSockets
* ⚡ Instant updates without page refresh
* 👥 Multiple users can connect and chat
* 🔄 Bi-directional communication (client ↔ server)
* 🌐 Lightweight and fast communication

---

## 🛠️ Tech Stack

* JavaScript
* WebSocket API
* Node.js (if backend used)
* HTML / CSS

---

## 📚 What I Learned

* How WebSockets work (handshake, connection lifecycle)
* Real-time client-server communication
* Managing multiple connections
* Broadcasting messages to all clients
* Difference between WebSocket and HTTP

---

## ⚙️ How It Works

WebSockets create a persistent connection between the client and server.
Unlike HTTP, the connection stays open, allowing real-time data exchange.

When a user sends a message:

1. It is sent to the server via WebSocket
2. The server broadcasts it to all connected clients
3. All users receive the message instantly

---

## ⚠️ Project Status

🚧 This project is still under development and can be improved further.

---

## 🔮 Future Improvements

* [ ] User authentication (login system)
* [ ] Chat rooms / group chat
* [ ] Online/offline user status
* [ ] Message timestamps
* [ ] UI/UX improvements
* [ ] Store messages (database integration)

---

## 📦 Installation

1. Clone the repository

```bash
git clone https://github.com/Dilan032/WebSocket-Chat.git
```

2. Navigate to the project folder

```bash
cd WebSocket-Chat
```

3. Install dependencies (if Node.js used)

```bash
npm install
```

4. Run the server

```bash
node server.js
```

5. Open in browser

```
http://localhost:3000
```

---

## 👨‍💻 Author

* Dilan Kanishka
* GitHub: https://github.com/Dilan032

---

## ⭐ Note

This project was built as part of my learning journey in real-time web technologies and WebSocket communication.
