##  Message Queues
A message queue is a queue of messages sent between applications. It includes a sequence of work objects that are waiting to be processed. ... Another application, called a consumer, connects to the queue and gets the messages to be processed. Messages placed onto the queue are stored until the consumer retrieves them.

![api](https://www.cloudamqp.com/img/blog/thumb-mq.jpg)

### What does it mean that web sockets are bidirectional? Why is this useful?
BIDIRECTIONAL. Whereas HTTP relies on a client request to receive a response from the server for every exchange, WebSockets allow for full-duplex bidirectional communication. This enables the server to send real-time updates asynchronously, without requiring the client to submit a request each time.
### Does socket.io use HTTP? Why?
Even when websockets can be used, the initial connection setup it done over HTTP. Also, a socket.io server will attach to an HTTP server so it can serve its own client code through /socket.io/socket.io.js .
### What happens when a client emits an event?
The event gets passed to the server through websockets. Its a tcp connection from the browser to the server. The connection is full duplex meaning the server can send real time data to the client and vise versa.
### What happens when a server emits an event?
The event gets passed to the server through websockets. Its a tcp connection from the browser to the server. The connection is full duplex meaning the server can send real time data to the client and vise versa.
### What happens if a client “misses” an event?
it misses it.
### How can we mitigate this?
we can use a message queue to reprocessed the event.

### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|Socket| A socket is one endpoint of a two-way communication link between two programs running on the network. |
|Web Socket|ebSocket is a computer communications protocol, providing full-duplex communication channels over a single TCP connection|
|Socket.io|Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers|
|Client|A system that uses remote services from a server.|
|Server|A system that provides services to other systems in its network.|
|OSI Model|a conceptual framework used to describe the functions of a networking system|
|TCP Model|It stands for Transmission Control Protocol/Internet Protocol. The TCP/IP model is a concise version of the OSI model. It contains four layers, unlike seven layers in the OSI model|
|TCP|The Transmission Control Protocol is one of the main protocols of the Internet protocol suite. It originated in the initial network implementation in which it complemented the Internet Protocol|
|UDP|is a lightweight data transport protocol that works on top of IP. UDP provides a mechanism to detect corrupt data in packets, but it does not attempt to solve other problems that arise with packets|
|Packets| is a formatted unit of data carried by a packet-switched network. A packet consists of control information and user data|

