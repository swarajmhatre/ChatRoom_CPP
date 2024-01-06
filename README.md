# Chat Server Project

This is a simple chat server implemented in C++ using the Winsock library. The server allows multiple clients to connect and exchange messages in a chat-like environment. The code is compatible with both Visual Studio and Visual Studio Code.

## Prerequisites

- Windows operating system
- Visual Studio or Visual Studio Code for development
- Putty for connecting multiple clients

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/chat-server.git
   ```

2. Open the project in your preferred C++ development environment (Visual Studio or Visual Studio Code).

3. Ensure that you have the Winsock library installed on your Windows system.

## Compilation and Running

### Visual Studio

1. Open the project in Visual Studio.
2. Build the solution (`Ctrl + Shift + B`).
3. Run the server by pressing `F5` or clicking on the "Start Debugging" button.

### Visual Studio Code

1. Open the project in Visual Studio Code.
2. Open a terminal in VS Code.
3. Compile the code using the following command:

   ```bash
   g++ main.cpp -lws2_32 -o myexe
   ```

4. Run the executable:

   ```bash
   ./myexe
   ```

## Connecting Clients

1. Use Putty to connect to the server.
2. Open Putty and select the "Raw" connection type.
3. Enter the server's IP address (127.0.0.1) and port (54000).
4. Click "Open" to establish a connection.

## Usage

- Clients can connect to the server using Putty.
- The server sends a welcome message to each connected client.
- To quit the server, type `\quit` in any connected client's terminal.

## Compilation and Running Command

For compiling and running the code manually using the terminal:

1. Compilation:

   ```bash
   g++ main.cpp -lws2_32 -o myexe
   ```

2. Running the executable:

   ```bash
   ./myexe
   ```

## Contributors

- [Swaraj Mhatre](https://github.com/swarajmhatre) (swarajmhatre)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
