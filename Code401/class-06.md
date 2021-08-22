# Authentication
![img](https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Middleware_Schema.svg/220px-Middleware_Schema.svg.png)

### Explain what a “Singleton” is (in Computer Science terms)
 A software design pattern that restricts the instantiation of a class to one "single" instance. This is useful when exactly one object is needed to coordinate actions across the system.
### Explain how the Singleton pattern can be used with Node modules, specifically with classes
instead of creating a new object we need to ensure the constructor was called only once and then we reuse the instance.
We can achieve this by refactoring our class to have:
- hidden (private)constructor
- public getInstance method that returns instance of the class
### If you were tasked with building a middleware system like Express uses, what approach might you take to construct/operate it?
Middleware literally means anything you put in the middle of one layer of the software and another. Express middleware are functions that execute during the lifecycle of a request to the Express server. Each middleware has access to the HTTP request and response for each route (or path) it’s attached to. In fact, Express itself is compromised wholly of middleware functions. Additionally, middleware can either terminate the HTTP request or pass it on to another middleware function using next (more on that soon). This “chaining” of middleware allows you to compartmentalize your code and create reusable middleware.

### Document the following Vocabulary Terms

|Term|Description|
|----|----|
|Router Middleware| Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router(). |
|Dynamic Module Loading| Dynamic loading is a mechanism by which a computer program can, at run time, load a library (or other binary) into memory, retrieve the addresses of functions and variables contained in the library, execute those functions or access those variables, and unload the library from memory. |
|Singleton Pattern|  a software design pattern that restricts the instantiation of a class to one "single" instance |
|CRUD -> REST Method Matches| POST Creates a new resource,GET Retrieves a resource,PUT Updates an existing resource,DELETE Deletes a resource.|
|Mock Testing| Mock testing is an approach to unit testing that lets you make assertions about how the code under test is interacting with other system modules. |
