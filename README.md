# Multithreaded-Chat-Application
*COMPANY*: CODTECH IT SOLUTIONS
*NAME*: ANAS KHAN
*INTERN ID*: CT0DKK359
*DOMAIN*: JAVA PROGRAMMING
*DURATION*: 8 WEEKS
*MENTOR*: NEELA SANTOSH
*DESCRIPTION:*

## 🧠 Project Overview

This project is a **multi-threaded chat application** built using core Java. It follows the **client-server architecture**, where a single server can handle multiple clients simultaneously using **Java Socket Programming** and **multithreading**. Each client can send and receive real-time messages, and the server broadcasts messages to all connected clients.

This project is a solid example of how real-time messaging systems work behind the scenes. It's highly educational for understanding concurrent programming and networking in Java.

## 🚀 Key Features

### ✅ 1. Real-Time Chat
- Clients can join the chat room and send/receive messages in real time.
- Server broadcasts each message to all other connected clients.

### ✅ 2. Multi-threaded Server
- The server uses **threads** to handle multiple clients at the same time.
- Each client connection spawns a new thread for message handling.

### ✅ 3. Simple & Scalable
- Easy-to-read, modular code.
- Can be extended into a group chat app or private chat system.

### ✅ 4. Unique Usernames
- Every client is asked to enter their name before chatting.
- Messages are tagged with the sender's name.

## ⚙️ Technologies Used

| Component     | Description |
|---------------|-------------|
| Java Sockets  | For TCP-based client-server communication |
| Threads       | Each client is handled in a separate thread |
| Scanner       | For reading user input from console |
| Streams       | InputStreamReader, BufferedReader, PrintWriter |

## 🧪 How It Works

### 🖥️ Server
- Listens on a fixed port (e.g., 1234).
- Accepts client connections.
- For every new client:
  - Starts a new thread.
  - Listens for their messages.
  - Broadcasts received messages to all other clients.

### 💬 Client
- Connects to the server using IP & port.
- Sends messages to server.
- Listens for messages from server and displays them.

## 🚀 How to Run

### Step 1: Start Server
- Open `Server.java` → Right-click → Run
- Console will show: `Server started...`

### Step 2: Run Multiple Clients
- Open `Client.java` → Right-click → Run
- Enter a name → Start chatting
- Repeat to open 2nd or 3rd client  
  (Enable “Allow parallel run” in IntelliJ if needed)

### Optional: Run via Terminal
```bash
javac Server.java
javac Client.java
java Server
# In new terminal tabs
java Client
java Client

## Output
