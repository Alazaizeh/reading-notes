![img](https://upload.wikimedia.org/wikipedia/commons/thumb/2/20/Middleware_Schema.svg/220px-Middleware_Schema.svg.png)

### 1. Name 3 real world use cases where you’d want to change the request with custom middleware
  1. database middleware 
  2. application server middleware
  3. message-oriented middleware
### 2. True or false: The route handler is middleware?
   False
### 3. In what ways can a middleware function end the process and send data to the browser?
   If the current middleware function does not end the request-response cycle, it must call next() to pass control to the next middleware function. Otherwise, the request will be left hanging.
### 4. At what point in the request lifecycle can you “inject” middleware?
   After receiving the request .
### 5. What can cause express to error with “Request headers sent twice, cannot start a second response”
   when submit twice the same request
|Term|Description|
|----|----|
|Middleware|Middleware is software that provides common services and capabilities to applications outside of what’s offered by the operating system. Data management, application services, messaging, authentication, and API management are all commonly handled by middleware.|
|Request Object|The req object represents the HTTP request and has properties for the request query string, parameters, body, HTTP headers, and so on|
|Response Object|The res object represents the HTTP response that an app sends when it gets an HTTP request.|
|Application Middleware|Bind application-level middleware to an instance of the app object by using the app.use() and app.METHOD() functions|
|Routing Middleware|Router-level middleware works in the same way as application-level middleware, except it is bound to an instance of express.Router().|
|Test Driven Development|Test-driven development is a software development process relying on software requirements being converted to test cases before software is fully developed, and tracking all software development by repeatedly testing the software against all test cases.|
|Behavioral Testing|Behavioural Testing is a testing of the external behaviour of the program, also known as black box testing. It is usually a functional testing.|
