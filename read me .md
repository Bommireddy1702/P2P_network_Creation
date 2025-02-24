Peer-to-Peer Chat Application

CS 216: Introduction to Blockchain

Assignment 2

Team Information
Team Name: Network Miner's
Team Members:
Bommireddy Varun Kumar Reddy(mc230041006)
Alam Sai Chathura(ce230004004)
kota Sanjay Kumar(cse230001042)

Project Description
The Peer-to-Peer (P2P) Chat Application is a decentralized communication system that allows multiple users to engage in real-time messaging without relying on a central server. This application is designed to facilitate simultaneous message sending and receiving through multi-threading, ensuring smooth and efficient communication.

Key Functionalities: 🔹 Multi-Peer Support – Enables multiple nodes to connect and interact within the network. 🔹 Peer Discovery & Tracking – Maintains an active list of connected peers. 🔹 Alphabetical Peer Sorting – Organizes peer names in a sorted order for faster searching and querying. 🔹 Custom Message Format – Ensures structured communication using the format: 🔹Message Broadcasting – Allow sending a message to multiple peers simultaneously. 🔹Peer Exit Handling-When a peer exits, it is automatically removed from the list of active peers, ensuring that it no longer appears in query results. Additionally, a notification message is broadcasted to all remaining peers, informing them of the peer's departure.


Features
Simultaneous Send & Receive (Multi-threading)
Peer Discovery & Tracking
Custom Message Format: <IP_ADDRESS:PORT> <TEAM_NAME>
Peer Exit Handling
Message Broadcasting
Bonus: Persistent Peer Connection (connect() function)

Prerequisites
Install dependencies: sudo apt update
sudo apt install g++
g++ --version
g++ -o my_program my_program.cpp
./my_program
How to Run
run in C++ with c++11 or c++17,

Usage
Upon starting, the following menu is displayed:

Enter your name: Netwirk Miner's Enter your port number: 45321 Ip address :127.0.0.1 Server listening on port 45600 & 45700

* Menu *

Send message
Query active peers
Connect to active peers
Quit
Sending Messages
Select 1 from the menu.
Enter the recipient's IP & port.
Type your message & press Enter.
Querying Peers
Select 2 from the menu.
List of active peers is displayed. 3.Arranging them in sorted order so that the node can check them easily
Exiting
Enter 0 to quit.
Sending exit removes a peer from the list.
Message Format
<IP_ADDRESS:PORT> <TEAM_NAME>

Example:

10.206.4.201:8080 blockchain Hello, you there?

Bonus Feature: connect()
Establishes persistent peer connections.
Newly connected peers appear in the query list.
Notes
Use fixed ports instead of ephemeral ports.
Avoid duplicate (IP:PORT) entries.
References
Socket Programming in C
Linux IP Address Guide
Threading in Python
GitHub Submission
Repository URL: [Your GitHub Repository Link]
Ensure your repository is public.
Upload:
Source code
Configuration files (if any)
README.md
Submit the GitHub link on Moodle.
Deadline:Submission Date: 22nd February 2025, 11:30 PM