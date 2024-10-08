# Socket.IO Chat Application

This project is a simple chat application built using Socket.IO, Express, and SQLite. It demonstrates how to set up a real-time chat application with message persistence and clustering for better performance.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Tutorial](#tutorial)

## Features

- Real-time messaging using Socket.IO
- Message persistence with SQLite
- Clustering for better performance
- Connection state recovery
- Simple and clean UI

## Prerequisites

- Node.js (v14 or later)
- npm (v6 or later)

## Installation

1. Clone the repository:

2. Install the dependencies:
   ```sh
   npm install
   ```

## Usage

1. Start the server:

   ```sh
   node index.js
   ```

2. Open your browser and navigate to [http://localhost:3000](http://localhost:3000) to start chatting.

## Project Structure

```
socketio-chat/
├── index.html
├── index.js
├── package.json
└── README.md
```

- **index.html**: The frontend of the chat application.
- **index.js**: The backend server using Express and Socket.IO.
- **package.json**: The project's dependencies and scripts.

## Technologies Used

- **Socket.IO**: Real-time communication library.
- **Express**: Web application framework for Node.js.
- **SQLite**: Lightweight database for message persistence.
- **Socket IO Cluster Adapter**: Node.js module for creating child processes.

## License

This project is licensed under the ISC License. See the LICENSE file for details.

## Tutorial

This project is based on the Socket.IO tutorial: [Socket.IO Tutorial](https://socket.io/docs/v4/).

Feel free to contribute to this project by opening issues or submitting pull requests. Happy chatting!
