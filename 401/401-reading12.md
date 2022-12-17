# Socket.io

[Return to Home](https://sethppierce.github.io/reading-notes)

## Questions

### Web Sockets

What is a Web Socket?

A Web Socket is a persistent connection between a client and a server that allows for bi-directional communication over a single TCP connection.

Describe the Web Socket request/response handshake and what happens once the connection is established.

In the Web Socket request/response handshake, the client sends a request to the server to connect to a Web Socket connection, and the server responds with an acknowledgement. Once the connection is established, the client and server can send messages back and forth without the need for a new request/response cycle.

Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.

request

### Socket.io Tutorial

What does the event handler io.on() do?

The event handler io.on() listens for a specific event and executes a callback function when that event is received.

Describe some possible proof of life or proof that the code works as expected

Adding Console.log, or using onAny with a logger function

What does socket.emit() do?

Socket.emit() sends an event to the server, with data.

### Socket.io vs Web Sockets

What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).

Socket.io is a library that utilizes WebSocket.

When would you use Socket.IO?

You would use Socket.IO when you want to use the additional features provided by socket.io

When would you use WebSockets?

When you don't need any of the additional features added by socket.io
