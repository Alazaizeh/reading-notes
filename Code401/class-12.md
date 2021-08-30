## Socket.io
Socket.IO is a JavaScript library for realtime web applications. It enables realtime, bi-directional communication between web clients and servers.

![api](https://www.technologyuk.net/computing/software-development/software-design/images/event_driven_01.gif)

### What is the benefit of transforming data into packets?
 To meet the demands of pervasive data-centric applications and services
### UDP is often refereed to as a connectionless protocol. Why is this?
UDP is a connectionless protocol. It is known as a datagram protocol because it is analogous to sending a letter where you don't acknowledge receipt.
### Can a socket server application have multiple socket connections?
Yes as long as they are associated with different client-side
### Can a socket connection application be connected to multiple socket servers?
No,A server socket listens on a single port. ... Multiple connections on the same server can share the same server-side IP/Port pair as long as they are associated with different client-side IP/Port pairs
### Can an application be both a socket server and a socket connection?
yes if we use two different ports. Or if the sockets won’t be using the same port at the same time.

### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|Observer Pattern|The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods|
|Listener| a listen socket that has an Internet Protocol (IP) address|
|Event Handler| used to handle and verify user input, user actions, and browser actions|
|Event Driven Programming|event-driven programming is a programming paradigm in which the flow of the program is determined by events|
|Event Loop|a programming construct or design pattern that waits for and dispatches events or messages in a program.|
|Event Queue| a repository where events from an application are held prior to being processed by a receiving program or system.|
|Call Stack| is a stack data structure that stores information about the active subroutines of a computer program. This kind of stack is also known as an execution stack, program stack, control stack, run-time stack, or machine stack|
|Emit/Raise/Trigger|We trigger the emitter via the emit() method, which pushes the event with the information we've provided.|
|Subscribe|To receive messages sent to a particular channel, you subscribe to it.|
|database|A database is an organized collection of structured information, or data, typically stored electronically in a computer system|
#### Helpful resources
[Node docs: events](https://nodejs.org/api/events.html )
