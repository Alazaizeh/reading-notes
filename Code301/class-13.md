![image](http://lofrev.net/wp-content/photos/2017/04/http_logo_dpwnload-250x150.png)

### In your own words, describe what each group of status code represents:
#### 100’s =
These are informational status codes; they usually tell the client that the header part of the request has been received and the server will try to comply with a transmission demand of the client.
#### 200’s = 
These are the success codes. They tell the client that its request was accepted
#### 300’s =
These are redirection codes. They tell the client that the resource they are requesting isn’t available at the expected location anymore. 
#### 400’s =
These are the client error codes. They are all about invalid requests a client sent to a server. 
#### 500’s 
These are the server error codes. Often they indicate problems with overwhelmed servers or unreachable servers behind proxies, but sometimes they can be directly related to client requests that trigger error exceptions on the server.=
### What is a status code 202?
202 Accepted - Often used for asynchronous processing. This code tells the client that the request was valid, but its processing will finish sometime in the future. 
### What is a status code 308?
308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore. 
### What code would you use if an update didn’t return data to a client?
204 No Content - A proper code for updates that don’t return data to the client, for example when just saving a currently edited document.
### What code would you use if a resource used to exist but no longer does?
308 Permanent Redirect - This tells the client to use another URL to access the resource and not use the current URL anymore.
### What is the ‘Forbidden’ status code?
403 Forbidden - The client has authorized or doesn’t need to authorize itself, but still has no permissions to access the resource.

![image](https://www.opc-router.de/wp-content/uploads/2021/03/mongodb_thumbnail.png)

### Why do we need to pull our MongoDB database string out of our server and put it into our .env?
To keep it secret
### What is middleware?
Middleware is a type of computer software that provides services to software applications beyond those available from the operating system.
### What does app.use(express.json()) do?
to recognize the incoming Request
### What does the /:id mean in a route?
Route parameters are named URL segments that are used to capture the values specified at their position in the URL. The captured values are populated in the req.params object, with the name of the route parameter specified in the path as their respective keys.
### What is the difference beween PUT and PATCH?
The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.
### How do you make a defalut value in a schema?
schemas can define default values for certain paths. If you create a new document without that path set, the default will kick in.
### What does a 500 error status code mean?
500 means Internal Server Error, which can be anything from a missing header field the backend accessed without checking its existence to an unreachable third party service the backend wanted to call.
### What is the difference between a status 200 and a status 201?
The 200 status code is by far the most common returned. It means, simply, that the request was received and understood and is being processed. A 201 status code indicates that a request was successful and as a result, a resource has been created
