![header](https://pcgservices.com/wp-content/uploads/2018/10/high_technology_industry.png)

### 1- What’s the difference between PUT and PATCH?
PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

### 2- Provide links to 3 services or tools that allow you to “mock” an API for development like json-server
1. https://mockoon.com
2. https://mockapi.io
3. https://www.mock-server.com
### 3- Compare and contrast Swagger and APIDoc.js 1 Which HTTP status codes should be sent with each type of (un)successful API call?

* **Popularity**: By comparing stats,  swagger-ui is more popular then apidocjs.

* **Consistency**: If we already using swagger for our Dotnetcore service, then implementing swagger tool will consist more from Info and UI prospective.

* **Implementation complexity**: apidocjs and swagger both required documentation content on implemented method as customize comment data. In addition they allow to write documentation data in separate resource file as .js and .json. If we already have swagger.json created by DotnetCore we can reuse more than 80% specification.

* **Maintenance**: For apidocjs will have to modify documentation for each affected method/endpoints if service changed. In swagger we can limit changes. But by implementing apidocjs we can isolate the layer.

* **Other benefits**: Because swagger use plain .json that could be parsed through programing language, thus we can get advantage of various other 3rd parties in order to create http client and more. 
* **Future**: Due to popularity of swagger, apidocjs provide information about apidoc-swagger converter so we can switch apidoc to swagger anytime.

### 4- Compare and contrast SOAP and ReST
**Soap Advantages**

SOAP provides the following advantages when compared to REST:
*    Language, platform, and transport independent (REST requires use of HTTP)
*    Works well in distributed enterprise environments (REST assumes direct point-to-point communication)
*    Standardized
*    Provides significant pre-build extensibility in the form of the WS* standards
*    Built-in error handling
*    Automation when used with certain language products

**REST Advantages**

REST is easier to use for the most part and is more flexible. It has the following advantages over SOAP:
*    No expensive tools require to interact with the web service
*    Smaller learning curve
*    Efficient (SOAP uses XML for all messages, REST can use smaller message formats)
*    Fast (no extensive processing required)
*    Closer to other web technologies in design philosophy
### Document the following Vocabulary Terms

| Term | Description |
| --- | ----------- |
| Web Server | On the software side, a web server includes several parts that control how web users access hosted files. At a minimum, this is an HTTP server. An HTTP server is software that understands URLs (web addresses) and HTTP (the protocol your browser uses to view webpages). An HTTP server can be accessed through the domain names of the websites it stores, and it delivers the content of these hosted websites to the end user's device. |
| Express | Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications. |
| Routing | Routing refers to how an application’s endpoints (URIs) respond to client requests |
| WRRC | Web request response cycle, details how information moves between client/server |
