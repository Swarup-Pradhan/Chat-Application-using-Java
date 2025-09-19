# 💬 Java Chat Application (Client-Server)

A simple **Java-based client-server chat application** built using **Sockets** and **Swing GUI**. This project demonstrates real-time communication between a server and a client over TCP.

## 🚀 Features

* 📡 **Server Setup**: Host a chat server on a specific port (default: `2802`).
* 👥 **Client Connection**: Clients can connect to the server by entering a username.
* 💬 **Real-time Messaging**: Send and receive messages instantly.
* 🔐 **Connection Approval**: Server decides whether to accept or reject a client.
* 🖥 **GUI Interface**: User-friendly interface built with **Java Swing**.
* ❌ **Quit/Shutdown**: Safe exit for both server and client.

## 🛠 Tech Stack

* **Language**: Java
* **Networking**: Sockets (TCP/IP)
* **UI**: Swing (JFrame, JTextArea, JTextField, JButton)

## 📂 Project Structure

```
📦 ChatApplication
 ┣ 📜 Server.java   # Runs the server and handles incoming client connections
 ┣ 📜 Client.java   # Connects to server and enables real-time messaging
 ┗ 📜 README.md     # Project documentation
```

## ▶️ How to Run

1. **Compile both files**:

   ```sh
   javac Server.java Client.java
   ```
2. **Run the Server** (must be started first):

   ```sh
   java Server
   ```
3. **Run the Client**:

   ```sh
   java Client
   ```
4. Enter usernames, connect, and start chatting 🎉

## 📌 Future Improvements

* ✅ Support multiple clients.
* ✅ Add message timestamps.
* ✅ Improve UI with styling.
* ✅ Encrypt communication for security.

---

## 👨‍💻 Author

Developed by **Swarup Pradhan ✨**
Feel free to connect via [LinkedIn](https://www.linkedin.com/in/swaruppradhan2005/) or [GitHub](https://github.com/Swarup-Pradhan) or contribute to this project!

---
