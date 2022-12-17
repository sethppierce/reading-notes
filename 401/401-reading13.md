# Message Queues

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Socket.io Chat Example

Explain to a non-technical recruiter what the Chat Example (above) does.

Allows users to send messages to each other in real-time using Socket.IO.

What proof of life are we getting on the backend from the above app?

A console.log of hello world

Socket.IO gives us the i0.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?

If you want to send a message to everyone except for a certain emitting socket, you would use the "broadcast" flag.

### Rooms

What is a room and how might a room be useful?

A room is a virtual space within a Socket.IO application where clients can join and communicate with each other. Rooms can be useful for creating chat rooms.

How do you join a room? How do you leave a room?

To join a room, you can use the "join" method and pass in the name of the room you want to join. To leave a room, you can use the "leave" method and pass in the name of the room you want to leave.

### Namespaces

What is a Namespace and what does it allow you to do?

They're like different "routes" of a socket.io application. It allows you to divide up different parts of the server.

Each namespace potentially has its own what? (hint: 3 things)

Each namespace potentially has its own connected clients, event handlers, and middleware.

Discuss a possible use case for separate namespaces

A possible use case for separate namespaces could be to create separate areas of an application for different types of users, such as administrators, moderators, and regular users.

