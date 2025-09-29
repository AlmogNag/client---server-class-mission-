# UDP Time Server & Client (C++ with Winsock2)

This project demonstrates a simple client-server communication model using **C++**, **Winsock2**, and the **UDP protocol**.  
The server listens for requests from a client and responds according to the message received.

- Sending '1' returns the current system time.  
- Sending '2' returns the message: "I'm feel good".  
- Sending '3' returns the message: "HOT!".  

---

## Features
- Server implemented with UDP sockets (non-connection oriented).  
- Client menu to send different requests.  
- Simple message-response interaction.  

---

## Project Structure
- **server.cpp** – UDP server implementation.  
- **client.cpp** – UDP client implementation.  

---

## Requirements
- Windows operating system.  
- Visual Studio or any C++ compiler with Winsock2 support.  
- Winsock library: `Ws2_32.lib` (included with Visual Studio).  

---

## Compilation and Execution

1. Open the project in Visual Studio or another C++ environment.  
2. Make sure that `Ws2_32.lib` is linked in your project settings.  
3. Compile both `server.cpp` and `client.cpp`.  
4. Run the server first: server.exe
5. Run the client: client.exe


## Client Menu
When running the client, you will see the following menu:

1 - Time?
2 - How are you?
3 - Weather?
4 - Exit


## Example Interaction
**Client input:**
1
**Server response:**
Time Client: Received: 24 bytes of "Mon Sep 29 21:34:12 2025"
