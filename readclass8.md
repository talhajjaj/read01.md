**API Design Best Practices**

- What does REST stand for?
REST stands for representational state transfer and was created by computer scientist Roy Fielding.
(https://www.redhat.com/en/topics/api/what-is-a-rest-api)

- REST APIs are designed around a _resources_.

- What is an identifer of a resource? Give an example.
Each REST API resource can be accessed by using a Uniform Resource Identifier (URI).
he URI must contain the correct connection information to successfully call the API. The connection information consists of the host name where the web management service is running, and the port number that the service is using.
example: https://server:port/streams/rest/instances/{restid}/hosts/{restid}

(refrence: https://www.ibm.com/docs/en/streams/4.1.0?topic=reference-uri-patterns)

- What are the most common HTTP verbs?
1. **HEAD**
2. **GET**
3. **PUT**
4. **PATCH**
5. **POST** 
(refrence : https://nordicapis.com/ultimate-guide-to-all-9-standard-http-methods/)


- What should the URIs be based on?

-Give an example of a good URI.
example.com/articles/3252
http://example.com/good-uri-design
(https://webmasters.stackexchange.com/questions/2105/what-is-good-uri-design)

-What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?
its bad thing,it is a common misconception that the REST API is more "chatty". If your API is too trivial, it is because you have designed the wrong resource for the customer, not because you have used REST. The misunderstanding of "REST means trivial" may come from the relational database specification that must look like a completely standardized REST-API.
i think it means to reapet the same thing .
(https://www.jamasoftware.com/blog/rest-api-design/)


- What status code does a successful GET request return?
200 OK
The server successfully processed the request. Generally, this means that the server provided the requested page.

- What status code does an unsuccessful GET request return?
404 Not Found
This means the server can't find the requested page. For instance, the server often returns this code if the request is for a page that doesn't exist on the server.

- 
-What status code does a successful POST request return?
307 Temporary Redirect
This means the requested resource resides temporarily under a different location, but the requester should continue to use the original location for future requests. In contrast to 302, the request method should not be changed when reissuing the original request. For instance, a POST request must be repeated using another POST request.

-What status code does a successful DELETE request return?
f a DELETE method is successfully applied, there are several response status codes possible:

A 202 (Accepted) status code if the action will likely succeed but has not yet been enacted.
A 204 (No Content) status code if the action has been enacted and no further information is to be supplied.
A 200 (OK) status code if the action has been enacted and the response message includes a representation describing the status.
(https://developer.mozilla.org/en-US/docs/Web/HTTP/Methods/DELETE)