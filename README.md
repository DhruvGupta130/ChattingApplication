# 💬 SimpleChatApp

A **full-fledged Java chat application** with a WebSocket server and client, enabling real-time communication between multiple users in a clean and interactive setup.

---

## ✨ Features

✅ Real-time chat between multiple users  
✅ Users join by providing their name  
✅ Server broadcasts messages to all connected clients (except the sender)  
✅ Lightweight Java WebSocket implementation  
✅ Clean, modular code for easy customization  
✅ Client and server components included

---

## 🏗 Project Structure

```

/server      → Java WebSocket server (SimpleServer.java)
/client      → Java WebSocket client (WebSocketClient.java)
/README.md   → Project description and instructions

````

---

## 🚀 Getting Started

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/simple-chat-app.git
cd simple-chat-app
````

### 2️⃣ Build the project

```bash
mvn clean install
```

### 3️⃣ Run the server

```bash
cd server
java -jar target/server.jar
```

The server will start on **ws\://localhost:8080**.

### 4️⃣ Run the client(s)

```bash
cd client
java -jar target/client.jar
```

Provide your name when prompted, and start chatting!

---

## 🔧 Dependencies

* Java 17+
* [java-websocket](https://github.com/TooTallNate/Java-WebSocket)
* Lombok
* SLF4J + Logback (for logging)

---

## 💡 Future Improvements

✨ Add a graphical (GUI) chat client
✨ Support private messaging / group chats
✨ Store and display chat history
✨ Add emojis, file sharing, or media messages

---

## 🛡 License

This project is open-source under the [MIT License](LICENSE).

---

> 🚀 Built for learning, experimenting, and building cool real-time applications with Java WebSockets.

```
