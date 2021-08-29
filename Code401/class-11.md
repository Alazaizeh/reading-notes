![api](https://www.technologyuk.net/computing/software-development/software-design/images/event_driven_01.gif)

### Event Driven Applications
is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision. In this article we’re going to go over how Event-Driven Programming works and how we can make the best use of it in our Node.js projects

### Event-driven programming
is a programming paradigm in which the flow of program execution is determined by events - for example a user action such as a mouse click, key press, or a message from the operating system or another program. An event-driven application is designed to detect events as they occur, and then deal with them using an appropriate event-handling procedure. The idea is an extension of interrupt-driven programming of the kind found in early command-line environments such as DOS, and in embedded systems

### How event-driven programming works
The central element of an event-driven application is a scheduler that receives a stream of events and passes each event to the relevant event-handler. The scheduler will continue to remain active until it encounters an event (e.g. "End_Program") that causes it to terminate the application. Under certain circumstances, the scheduler may encounter an event for which it cannot assign an appropriate event handler.

### Why is access control important?
Access controls limit access to information and information processing systems.
### Describe an application that would need access control.
online forum
### What is a role used for?
used to facilitate administration of security in large organizations with hundreds of users and thousands of permissions. 
### Why is role based access control more scalable than discretionary or mandatory access control?
because of the roles in RBAC refer to the levels of access that employees have to the network. Employees are only allowed to access the information necessary to effectively perform their job duties
### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|Authorization|Authorization is the function of specifying access rights/privileges to resources|
|Role Based Access Control|becquse Role-based access control is a method of restricting network access based on the roles of individual users within an enterprise. |
|Capabilities| a secure way for linked data systems to grant and express authority utilizing|


#### Helpful resources
[Node docs: events](https://nodejs.org/api/events.html )
