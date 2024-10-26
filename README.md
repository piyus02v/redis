# Redis Clone in C/C++

A simple Redis-like key-value store built in C/C++, created to explore how in-memory databases work under the hood.

## Key Features

- **Data Structures**: Implements core Redis data structures like strings, lists, hash maps, and sets.
- **Event Loop**: A single-threaded event loop to handle multiple client requests in real-time.
- **Persistence**: An in-memory data store with basic save functionality for persistence.
- **Socket Programming**: Uses socket programming to manage client-server communication, enabling data exchange over TCP/IP.
- **Multithreading**: Allows handling of multiple clients for concurrent connections.

## Socket Programming Overview

This project uses **sockets** to enable network communication between clients and the server. Here’s a quick rundown of how it works:

- **Server Socket Setup**: The server creates a socket, binds it to a specified port, and listens for incoming client connections.
- **Client Connections**: Each client connects to the server’s IP address and port, establishing a communication link.
- **Data Exchange**: The server processes requests received via sockets, interprets commands, and sends responses back to the client.

This setup enables multiple clients to connect to the server simultaneously and interact with the data store through Redis-like commands.


## Getting Started

1. Clone and navigate to the project:
   ```bash
   git clone https://github.com/piyus02v/redis.git
2. Compile the code
   ```bash
   make
3. Run the server
   ```bash
   ./redis-server
   
## Example Commands

- `SET key value` – Stores a key-value pair.
- `GET key` – Retrieves the value of a key.
- `DEL key` – Deletes a key.
- `INCR key` – Increments the integer value of a key.
- `HSET hash field value` – Sets a field in a hash.

## Contributing

If you're interested in improving or learning more about Redis internals, feel free to open issues or submit pull requests!
