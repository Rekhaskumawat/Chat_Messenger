# Chat_Application_project

> A simple two-way chat application built using Java Sockets and a Swing-based GUI. This project demonstrates how a client and server can communicate through messages in real-time, with all messages being displayed directly inside the GUI.
## Overview:
        -> This project is a simple Client–Server Chat Application built using Java Sockets.
        -> The client application includes a Graphical User Interface (GUI) built with Swing, allowing the user to send and receive messages in real-time.
        -> The server accepts client connections, receives messages, and sends responses.
        -> The client displays both sent and received messages inside the chat window.

##  Features:
	-> Real-time bi-directional chat (Client <-> Server)
	-> GUI built using Java Swing
	-> Messages appear in a scrollable chat area
	-> Automatically displays:
		“You: <message>”
		“Server: <message>”
        -> Text field + Send button for user input
	-> Handles clean disconnection (END keyword)
	-> No message saved on disk — only displayed inside GUI

## Tech Stack:
	->Java 8+
	->Java Swing for GUI
	->Socket Programming

## How to Run the Project:
	Step1 : Start the Server
		Compile and Run the Server
		The server GUI will open and start listening on port 2300 . you can change the port number on the line number 65 in the file ChatServerGUI.java
	Step2 : start the Client
		Compile and run the Client
		The client GUI will open and connect to the server. you can change the host and thr port number at the line number 64 in the file ChatClientGUI.java

## Author : Rekha ShankarLal Kumawat 
