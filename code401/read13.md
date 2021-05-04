# Read 13

## Review, Research, and Discussion

**What does it mean that web sockets are bidirectional? Why is this useful?** The client or server can send a message to the other whenever a message is available. You can efficiently push data from the server to the client. [resource](https://blockchain.dcwebmakers.com/blog/intro-to-real-time-bidirectional-communications-between-browsers-and-websocket-servers.html#:~:text=WebSocket%20is%20an%20application%2Dlayer,between%20a%20web%20browser%20and)

**Does socket.io use HTTP? Why?** Yes. It has reliability because it falls back to HTTP long-polling in case the connection cannot be established. [resource](https://socket.io/docs/v4/index.html)

**What happens when a client emits an event?** The client will emit the event to the server. There's a way to even emit the event to all connected clients.

**What happens when a server emits an event?** Client needs a listener that listens for the event. The server will then emit the event to the client.

**What happens if a client “misses” an event?** The server will try to reconnect after the given delay. [resource](https://socket.io/docs/v3/client-socket-instance/)

**How can we mitigate this?** Make sure that we're connected. [resource](https://socket.io/docs/v3/client-socket-instance/)

## Term

- **Socket** An endpoint of a communication between two programs running on a network [resource](https://zetcode.com/javascript/socket/)
- **Web Socket** A bidirectional communication between the Client and the Server over a TCP connection. [resource](https://www.educba.com/websocket-vs-socket-io/)
- **Socket.io** a library that enables real-time and full-duplex communication between the Client and the Web servers. [resource](https://www.educba.com/websocket-vs-socket-io/)
- **Client** the library that runs inside the browser
- **Server** the library for Node.js
- **OSI Model**  the OSI model helped standardize the way computer systems send information to each other. [resource](https://www.freecodecamp.org/news/osi-model-networking-layers-explained-in-plain-english/)
- **TCP Model** A protocol for sending information between computers
- **TCP** Transmission Control Protocol
- **UDP** A communications protocol that is primarily used for establishing low-latency and loss-tolerating connections between applications on the internet. [resource](https://searchnetworking.techtarget.com/definition/UDP-User-Datagram-Protocol)
- **Packets** Packet creates pre-compiled, pure-JavaScript, binary parsers and serializers that are incremental through a binary pattern language that is declarative and very expressive. [resource](https://www.npmjs.com/package/packet)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
1. OSI Model but I would still like some additional clarification
1. TCP Model but again, I would like some additional clarification
1. Socket.io

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. Understanding more about emitting events
1. Socket.io rooms
1. Socket.io broadcasting

**What are you most excited about trying to implement or see how it works?** Emitting events sound super interesting!

## Readings
[Socket.io Chat Example](https://socket.io/get-started/chat/)
[Rooms and Namespaces](https://socket.io/docs/v3/rooms/index.html)
[Socket.io Emit Cheatsheet](https://socket.io/docs/v3/emit-cheatsheet/index.html)

[<== Back](https://simoneodegard.github.io/reading-notes/)