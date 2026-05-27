# Multiuser Chatroom App

A real-time multiuser chat application built using WebSockets and Socket.IO.  
Users can join different chat rooms, send messages instantly, and see active users in the room.

## Features

- Real-time messaging
- Multiple chat rooms
- Join/Leave notifications
- Active users list
- Simple and responsive UI
- WebSocket communication using Socket.IO

## Tech Stack

- HTML
- CSS
- JavaScript
- Node.js
- Express.js
- Socket.IO (WebSockets)

## Screenshots

### Join Room Page

Users can enter a username and choose a chat room.

### Chat Room

- Real-time messaging
- Sidebar with active users
- Leave room functionality

## Installation

Clone the repository:

```bash
git clone https://github.com/harshrajput-0/chatroom-app.git
```

Go to the project directory:

```bash
cd your-repo-name
```

Install dependencies:

```bash
npm install
```

Start the server:

```bash
npm start
```

Open in browser:

```txt
http://localhost:3000
```

## Project Structure

```txt
├── public
│   ├── css
│   ├── js
│   ├── chat.html
│   └── index.html
├── utils
│   ├── messages.js
│   └── users.js
├── server.js
├── package.json
└── README.md
```

## How It Works

- Users join a selected room.
- Socket.IO establishes a WebSocket connection.
- Messages are broadcasted to users inside the same room.
- User join/leave events update the active users list.

## Future Improvements

- Private messaging
- Authentication
- Typing indicators
- Message timestamps
- Database storage
- Mobile optimization

## Author

Harsh

## License

This project is open source and available under the MIT License.
