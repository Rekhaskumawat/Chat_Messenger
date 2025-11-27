# Chat_Application_project

 ### A simple two-way chat application built using Java Sockets and a Swing-based GUI. 
 ### This project demonstrates how a client and server can communicate through messages in real-time, with all messages being displayed directly inside the GUI.

## Overview:

1. This project is a simple Client–Server Chat Application built using Java Sockets.
2. The client application includes a Graphical User Interface (GUI) built with Swing, allowing the user to send and receive messages in real-time.
3. The server accepts client connections, receives messages, and sends responses.
4. The client displays both sent and received messages inside the chat window.

##  Features:

1. Real-time bi-directional chat (Client <-> Server)
2. GUI built using Java Swing
3. Messages appear in a scrollable chat area
4. Automatically displays:
		“You: <message>”
		“Server: <message>”
5. Text field + Send button for user input
6. Handles clean disconnection (END keyword)
7. No message saved on disk — only displayed inside GUI

## Tech Stack:

1. Java 8+
2. Java Swing for GUI
3. Socket Programming

## How to Run the Project:

### Step1 : -> Start the Server
		-> Compile and Run the Server
		-> The server GUI will open and start listening on port 2300 .
		-> you can change the port number on the line number 65 in the file ChatServerGUI.java

### Step2 : ->start the Client
		-> Compile and run the Client
		-> The client GUI will open and connect to the server.
		-> you can change the host and thr port number at the line number 64 in the file ChatClientGUI.java

