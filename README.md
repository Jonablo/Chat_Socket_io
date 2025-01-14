
# Chat_Socket_io

[![Node.js](https://img.shields.io/badge/Node.js-v18.x-green)](https://nodejs.org/)
[![Socket.io](https://img.shields.io/badge/Socket.io-v4.x-blue)](https://socket.io/)

A real-time chat application built with **Socket.IO** and **Node.js**, demonstrating how to implement real-time communication using WebSockets.

## 🌟 Features

- Real-time messaging.
- User connection and disconnection notifications.
- User-friendly interface for multiple users.
- Scalability and support for simultaneous connections.

## 📋 Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (version 18 or higher)
- [npm](https://www.npmjs.com/) (included with Node.js)

## 🚀 Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/Jonablo/Chat_Socket_io.git
   cd Chat_Socket_io
   ```

2. Navigate to the **Cliente** and **Server** folders to install their dependencies:

   ```bash
   # For the client
   cd Cliente
   npm install
   ```
   ```bash
   # For the server
   cd ../Server
   npm install
   ```

3. Start both services separately:

   ```bash
   # From the Cliente folder
   npm start
   ```

   ```bash
   # From the Server folder
   npm start
   ```

4. Open your browser at:

   ```
   http://localhost:3000
   ```

## 🛠️ Technologies Used

- **Node.js**: Backend platform.
- **Socket.IO**: Real-time communication library.
- **HTML, CSS, JavaScript**: Main components for the client interface.

## 📂 Project Structure

```plaintext
Chat_Socket_io/
├── Cliente/
│   ├── index.html
│   ├── style.css
│   └── script.js
├── Server/
│   ├── server.js
│   └── package.json
├── README.md
└── LICENSE
```

## 🤝 Contributions

Contributions are welcome! If you want to improve this project, follow these steps:

1. Fork the repository.
2. Create a branch for your changes (`git checkout -b feature/new-feature`).
3. Commit your changes (`git commit -m 'Add a new feature'`).
4. Push the branch (`git push origin feature/new-feature`).
5. Open a Pull Request.

## 📄 License

This project is licensed under the [MIT License](LICENSE). You can use, modify, and distribute it as needed.