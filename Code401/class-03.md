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
|Middleware||
|Request Object||
|Response Object||
|Application Middleware||
|Routing Middleware||
|Test Driven Development||
|Behavioral Testing||
