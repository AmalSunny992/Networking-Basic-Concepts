# HTTP
## HTTP Methods
You’ve probably heard about Hypertext Transfer Protocol, also known as HTTP. 
HTTP allows you to interact with Web pages, HTML documents, and APIs. 
It is the foundation of any data exchange on the Internet. 
A typical DevOps engineer works with HTTP every day and should have a solid knowledge of this protocol.

As a DevOps engineer, you should know what an HTTP request is, the various HTTP request methods that exist, and how they are different from each other.
An HTTP request is a request message from a client to a server asking for access to a resource.
There are 7 main HTTP request methods:

![image](https://github.com/AmalSunny992/networkingconcepts/assets/169422802/924f1860-c015-4628-ab73-905b692e14a9)

## HTTP Response Codes
Response codes indicate whether a request was completed successfully or failed. 
You’ve probably seen them floating around in pop culture references or been on the receiving end of a hyperlink that goes nowhere.

There are 4 categories of HTTP responses:

200s: Successful responses
300s: Redirects
400s: Client errors
500s: Server errors
Take a look at some of the most common response codes:

![image](https://github.com/AmalSunny992/networkingconcepts/assets/169422802/e5d6761c-bd92-4f88-afe1-b3c9337c328c)

## HTTP Headers
HTTP headers allow the client to add additional information to a request for purposes such as authentication, caching, and specifying the type of client device sending the request. 
Headers are widely used to control traffic and implement features such as canary releases, blue-green deployments, and a/b testing.

Headers fall into 4 general contexts:

1. General Header: A header that works for both response and requests messages.
2. Request Header: A header that only applies to request messages from a client.
3. Response Header: A header that only applies to responses from a server.
4. Entity Header: A header that gives information about the entity itself or the resource requested.
   Headers are case-insensitive in the structure Name: Value.
