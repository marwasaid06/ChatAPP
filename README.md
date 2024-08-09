# ChatAPP
Project Title: Simple Java Chat Application
Description
The Simple Java Chat Application allows multiple users to connect to a central server, exchange messages, and engage in real-time conversations. Whether you’re building a virtual coffee shop or coordinating with friends, this application has you covered!

Table of Contents
Installation
Usage
Contributing
License
Installation
To run the chat application locally, follow these steps:

Clone the Repository:
Open your terminal or command prompt.
Run the following command:
git clone https://github.com/your-username/simple-java-chat.git

Compile and Run the Server:
Navigate to the project directory:
cd simple-java-chat

Compile the server class:
javac ChatServer.java

Start the server:
java ChatServer

Compile and Run the Client:
In a separate terminal, navigate to the project directory.
Compile the client class:
javac ChatClient.java

Start a client:
java ChatClient

Usage
Server Side:
The server will listen for incoming connections on a specified port (e.g., 8080).
It assigns a unique user ID to each connected client.
Messages received from clients are broadcast to all connected users.
Client Side:
Connect to the server using the client application.
Input your messages and hit Enter to send them.
Receive messages from other users in real time.
Contributing
Contributions are welcome! If you’d like to improve this chat application, follow these steps:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push your branch to your forked repository.
Open a pull request.
License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as needed
