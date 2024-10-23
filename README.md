# Simple Chat Application
A basic chat application built in Python using sockets, designed to run locally on a single machine. This application allows multiple users to communicate with each other through a command-line interface.

# Features
Real-time Messaging: Send and receive messages in real time.  
Multi-client Support: Connect multiple clients to the server.  
Local Communication: Designed for local network use, eliminating the need for internet connectivity.  
Command-line Interface: Simple text-based interface for easy interaction.  

# Requirements
Python 3.x  

# Installation
Clone the repository:  
git clone <repository-url>  
cd simple-chat-app  
Run the server:  
python server.py  
In another terminal, run the client:  
python client.py  

# Usage
Start the Server: Run server.py to start the chat server. It will listen for incoming connections from clients.  
Connect Clients: Open multiple terminal windows and run client.py in each one to start multiple chat clients.  
Send Messages: Type your messages in the client terminal and press Enter to send. All connected clients will receive the messages in real time.  

# Example
To connect clients, you can run the following commands in different terminal windows:  

Terminal 1 (Server):  
python server.py  

Terminal 2 (Client 1):  
python client.py  

Terminal 3 (Client 2):  
python client.py  
