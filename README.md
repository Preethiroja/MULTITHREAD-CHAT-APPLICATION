# MULTITHREAD-CHAT-APPLICATION

COMPANY: CODTECH IT SOLUTION

NAME: PREETHI ROJA G

INTERN ID: CT04DH1206

DOMAIN: JAVA PROGRAMMING

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

# TASK DESCRIPTION

This project demonstrates a basic client-server chat application using Java sockets. It allows multiple clients to connect to a server and exchange messages in real-time, simulating a basic group chat system.
Components:
ChatServer.java:
Acts as a central server that accepts multiple client connections on port 1234.
Maintains a list of connected clients using a Set<ClientHandler>.
Listens for incoming messages from clients and broadcasts them to all other connected clients.
Removes clients gracefully when they disconnect or type "exit".

ChatClient.java:
Connects to the server running on "localhost" and port 1234.
Prompts the user for a name and sends/receives messages to/from the server.
Uses a separate thread to continuously listen for messages from the server while allowing user input.

Key Features:
Multi-client support using multithreading (Thread class).
Graceful handling of client join/leave.
Real-time message broadcasting using shared resources (PrintWriter).
Easy termination using "exit" command.

Use Case:
This project is suitable for:
Learning socket programming in Java.
Understanding multi-threaded server development.
Building foundational knowledge for chatbots, networked games, or online collaboration tools.

# OUTPUT

<img width="1305" height="238" alt="Image" src="https://github.com/user-attachments/assets/ef35a4d3-61aa-4051-89fa-98ea475af7c0" />
