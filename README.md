# ChatCode.io

ChatCode.io is a simple TCP-based chat application developed in C that allows real-time communication between a client and a server. This application demonstrates the use of sockets for network programming and provides a basic framework for a chat application.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [How to Run the Application](#how-to-run-the-application)
  - [Prerequisites](#prerequisites)
  - [Instructions](#instructions)
- [Example Usage](#example-usage)

## Features

- **Real-Time Communication**: Bidirectional communication between the client and server.
- **Message Exchange**: Send and receive messages in real-time.
- **Multi-platform Compatibility**: Works on any platform that supports C and socket programming.

## Technologies Used

- **Programming Language**: C
- **Networking**: Sockets (TCP/IP)
- **Libraries**: 
  - `arpa/inet.h` for Internet operations
  - `unistd.h` for POSIX operating system API
  - `string.h` for string manipulation
  - `stdio.h` for standard input/output

## How to Run the Application

### Prerequisites

- A C compiler
- Terminal/command prompt access

### Instructions

1. **Clone the Repository**

   Clone the repository from GitHub to your local machine:

   ```bash
   git clone https://github.com/Eshitacodes/ChatCode.io.git
   cd ChatCode.io
  
2. **Compile the Server and Client**

    Open a terminal in the project directory and compile the server and client code:
    
    ```bash
    gcc -o server server.c
    gcc -o client client.c
    ```

3. **Run the Server**
   
   In one terminal window, start the server:
   ```bash
   ./server
   ```
   The server will begin listening on port 3000.

4. **Run the Client**
   
   In another terminal window, start the client:
   ```bash
   ./client
   ```
   The client will connect to the server on port 3000. You can now start chatting!

## Example Usage

- **Client Side**:Type your message in the client terminal and press Enter to send it to the server.
- **Server Side**:Messages from the server will appear in the client terminal.
- Type "exit" to end the chat on either the client or server side.
- To close the terminal running the server or client, press Ctrl + C.
