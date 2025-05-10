# Client-Server-Project

This project demonstrates a basic **TCP client-server model** implemented in Java. It simulates real-world client-server communication, where a client sends messages to a server and receives responses. This setup is ideal for understanding how networked applications communicate using sockets.

## 🧩 Project Structure

- `Server.java`:  
  Implements the server-side logic. It listens for client connections, accepts incoming messages, and sends back responses.

- `TCPClient.java`:  
  Acts as the client that connects to the server via a socket, sends data, and processes responses.

## ⚙️ How It Works

1. The server runs and listens on a specified port.
2. The client connects to the server using that port.
3. The client sends a message to the server.
4. The server receives the message, processes it (echo or logic), and sends back a response.
5. Both server and client can handle multiple messages in a single session (can be extended).

## 🚀 Getting Started

### Prerequisites

- Java JDK 8 or later
- Command line or IDE (e.g., IntelliJ IDEA, Eclipse)

### Run the Server

```bash
javac Server.java
java Server
