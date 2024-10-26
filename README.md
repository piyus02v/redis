# Redis Clone in C/C++

A simple Redis-like key-value store built in C/C++, created to explore how in-memory databases work under the hood.

## Key Features

- **Data Structures**: Implements Redis core data structures like strings, lists, hash maps, and sets.
- **Event Loop**: A basic single-threaded event loop to handle client requests in real-time.
- **Persistence**: In-memory data store with basic save functionality for persistence.
- **Multithreading**: Allows handling of multiple clients for concurrent connections.

## Getting Started

1. Clone and navigate to the project:
   ```bash
   git clone https://github.com/piyus02v/redis.git
   
## Example Commands

- `SET key value` – Stores a key-value pair.
- `GET key` – Retrieves the value of a key.
- `DEL key` – Deletes a key.
- `INCR key` – Increments the integer value of a key.
- `HSET hash field value` – Sets a field in a hash.

## Contributing

If you're interested in improving or learning more about Redis internals, feel free to open issues or submit pull requests!
