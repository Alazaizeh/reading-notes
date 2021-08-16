![api](https://brands.home-assistant.io/_/rest/logo.png)
### What does REST stand for?
Representational State Transfer
### REST APIs are designed around a ____.
resources, which are any kind of object, data, or service that can be accessed by the client.
### What is an identifer of a resource? Give an example.
A resource has an identifier, which is a URI that uniquely identifies that resource. For example, the URI for a particular customer order might be:

`https://adventure-works.com/orders/1`
### What are the most common HTTP verbs?
 The most common operations are GET, POST, PUT, PATCH, and DELETE.
### What should the URIs be based on?
nouns and not verbs
### Give an example of a good URI.
`
https://adventure-works.com/orders
`
### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
APIs that expose a large number of small resources. Such an API may require a client application to send multiple requests to find all of the data that it requires. Instead, you might want to denormalize the data and combine related information into bigger resources that can be retrieved with a single request, thats why we should avoid "chatty".
### What status code does a successful GET request return?
200
### What status code does an unsuccessful GET request return?
404
### What status code does a successful POST request return?
201
### What status code does a successful DELETE request return?
204
