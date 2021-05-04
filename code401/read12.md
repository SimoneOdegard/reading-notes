# Read 12

## Review, Research, and Discussion

**What is the benefit of transforming data into packets?** Packet-based networks are more cost-effective, efficient, and scalable networks for content delivery. [resource](https://blog.fntsoftware.com/network-transformation-transitioning-to-packet-technology/)

**UDP is often refereed to as a connectionless protocol. Why is this?** This is because UDP doesn't establish a connection before sending data. It just send. [resource](https://en.wikibooks.org/wiki/Communication_Networks/TCP_and_UDP_Protocols/UDP#:~:text=Unlike%20TCP%2C%20UDP%20doesn't,UDP%20is%20called%20%22Connectionless%22.)

**Can a socket server application have multiple socket connections?** Yes, and the maximum number of sockets is 65535. [resource](https://www.ibm.com/docs/en/zos/2.3.0?topic=domain-maximum-number-sockets)

**Can a socket connection application be connected to multiple socket servers?** Yes, you can separate out the incoming socket.io and have separate socket.io server instances. [resource](https://stackoverflow.com/questions/60029843/multiple-socket-io-servers-sharing-a-single-http-s-server)

**Can an application be both a socket server and a socket connection?** Yes but you would need two different ports. [resource](https://www.quora.com/Can-you-make-a-client-socket-and-a-server-socket-in-one)

## Terms

- **Observer Pattern** The Observer pattern offers a subscription model in which objects subscribe to an event and get notified when the event occurs [resource](https://www.dofactory.com/javascript/design-patterns/observer#:~:text=The%20Observer%20pattern%20offers%20a,event%20driven%20programming%2C%20including%20JavaScript.&text=The%20event%20and%20event%2Dhandler,of%20the%20Observer%20design%20pattern.)
- **Listener** An event listener is a procedure in JavaScript that waits for an event to occur. The simple example of an event is a user clicking the mouse or pressing a key on the keyboard. [resource](https://www.geeksforgeeks.org/javascript-addeventlistener-with-examples/)
- **Event Handler** JavaScript applications in the Navigator are largely event-driven. Events are actions that occur, usually as a result of something the user does. [resource](http://home.ubalt.edu/abento/701/javascript/eventehand.html)
- **Event Driven Programming** JavaScript in the browser uses an event-driven programming model. Everything starts by following an event. The event could be the DOM is loaded, or an asynchronous request that finishes fetching, or a user clicking an element or scrolling the page, or the user types on the keyboard. [resource](https://flaviocopes.com/javascript-events/)
- **Event Loop** An Event Loop monitors the Call Stack and the Callback Queue.
- **Event Queue** The event queue is responsible for sending new functions to the track for processing. It follows the queue data structure to maintain the correct sequence in which all operations should be sent for execution. Whenever an async function is called, it is sent to a browser API. These are APIs built into the browser. [resource](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)
- **Call Stack** The call stack is responsible for keeping track of all the operations in line to be executed. Whenever a function is finished, it is popped from the stack. [resource](https://www.educative.io/edpresso/what-is-an-event-loop-in-javascript)
- **Emit/Raise/Trigger** All used with events. They seem to all fire off or activate the event.
- **Subscribe** It will subscribe itself to the observable of interest. [resource](https://stackoverflow.com/questions/42000883/what-does-the-subscribe-function-do)
- **database** An organized collection of structured information or data. [resource](https://www.oracle.com/uk/database/what-is-database/)

## Preview

**Which 3 things had you heard about previously and now have better clarity on?**
Everything in the previews were very new to me.

**Which 3 things are you hoping to learn more about in the upcoming lecture/demo?**
1. WebSockets and Socket.IO
1. TCP
1. Open System Interconnection Model (OSI Model)

**What are you most excited about trying to implement or see how it works?** I'm excited to learn more about WebSockets/Socket.IO. It seems like they will be super useful.

## Readings
[OSI Model Explained](https://www.youtube.com/watch?v=vv4y_uOneC0)
[TCP Handshakes Explained](https://www.youtube.com/watch?v=xMtP5ZB3wSk)
[Web Sockets](https://en.wikipedia.org/wiki/WebSocket)
[Socket.io Tutorial](https://www.tutorialspoint.com/socket.io/)
[Socket.io vs Web Sockets](https://www.educba.com/websocket-vs-socket-io/)

[<== Back](https://simoneodegard.github.io/reading-notes/)