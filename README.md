# Chat_Messenger

## 📌 Project Description

A simple two-way chat application built using Java Sockets and a Swing-based GUI. 
This project demonstrates how a client and server can communicate through messages in real-time, with all messages being displayed directly inside the GUI.

---

## 📂 Project Structure

```
Chat_Messenger/
│
|----ChatClientGUI.java
|----ChatServerGUI.java
|----README.md

```
---

## 📖 Overview:

1. This project is a simple Client–Server Chat Application built using Java Sockets.
2. The client application includes a Graphical User Interface (GUI) built with Swing, allowing the user to send and receive messages in real-time.
3. The server accepts client connections, receives messages, and sends responses.
4. The client displays both sent and received messages inside the chat window.

---

## 🚀 Features

1. Real-time bi-directional chat (Client <-> Server)
2. GUI built using Java Swing
3. Messages appear in a scrollable chat area
4. Automatically displays:
		“You: <message>”
		“Server: <message>”
5. Text field + Send button for user input
6. Handles clean disconnection (END keyword)
7. No message saved on disk — only displayed inside GUI

---

## 🛠 Technologies Used

1. Java 8+
2. Java Swing for GUI
3. Socket Programming

---

## 💻 Get Started

### ✅ Prerequisites

1. Java JDK 8 or later installed
2. Terminal or preferred IDE (IntelliJ , VS code , etc.) / Notepad / Editor(Editing the host if connection to be done between two different devices {Optional srep})

### 🔗 Connection

#### For using the same deivce as Server and Client as well.

   1. First run **ChatServerGUI.java**
   2. Then run **ChatClientGUI.java** on another terminal

#### For using two different devices (using the actual concept of networking between two devices)

1. Both the devices should be connected to the same wifi OR by connecting LAN cable to both the devices
2. Get the IP address of network from device which will run the ChatServerGUI.java (Windows : CMD : ipconfig : select the IPV4 address)
3. Paste this IP address to the 64th line of ChatClientGUI.java in place of host ; ie. "localhost"
4. Run **ChatServerGUI.java** first
5. Then run the **ChatClientGUI.java** from the other device
