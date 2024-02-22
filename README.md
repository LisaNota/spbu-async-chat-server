# Asynchronous Chat Server

This project aims to create an asynchronous chat server that can serve multiple clients simultaneously and allows them to exchange messages in real-time.

## Requirements:

1. **Server:** Develop an asynchronous server using the `asyncio` library, which listens on a specific port for incoming connections.
2. **Clients:** Write an asynchronous client script that can connect to the server and send messages.
3. **Concurrency:** The server should be capable of handling multiple client connections concurrently using multiple `asyncio` tasks (coroutines).
4. **Chat Rooms:** Add support for chat rooms where users can choose which room they want to enter.
5. **Message Broadcasting:** The server should broadcast messages from one client to all participants in the room.
6. **Asynchronous Events:** Utilize `asyncio.Queue` for handling asynchronous events, such as receiving a new message from a client.
7. **Exceptions and Error Handling:** Handle exceptions to ensure that incorrect client behavior does not stop the server.
8. **Additional Features:** Implement additional features such as private messages.

## Code Overview:

### Server.py
- Implements the asynchronous chat server.
- Handles client connections, message reception, and broadcasting.
- Utilizes `asyncio` for asynchronous event handling.
- Utilizes a Tkinter GUI for displaying server status and messages.

### Client.py
- Implements the asynchronous chat client.
- Connects to the server, sends messages, and receives messages.
- Utilizes `asyncio` for asynchronous event handling.
- Utilizes a Tkinter GUI for user interaction.

## Usage:
1. Run `Server.py` to start the chat server.
2. Run multiple instances of `Client.py` to connect to the server and exchange messages.
