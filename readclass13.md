**CRUD**


- In your own words, describe what each group of status code represents:


100’s = its an interim response, Indicates the client that the initial part of the request has been received and has not yet been rejected by the server.


200’s = its means ok, and its indicates that the REST API successfully carried out whatever action the client requested and that no more specific code .


300’s = its means thats theres multiple choices.


400’s = means its a bad request, and the generic client-side error status.
500’s =Internal Server Error,500 is the generic REST API error response. Most web frameworks automatically respond with this response status code whenever they execute some request handler code that raises an exception.


- What is a status code 202?
A 202 response is typically used for actions that take a long while to process. It indicates that the request has been accepted for processing, but the processing has not been completed.(accepted).


- What is a status code 308?
308 Permanent Redirect

- What code would you use if an update didn’t return data to a client?
204 no content


- What code would you use if a resource used to exist but no longer does?
404 not found

- What is the ‘Forbidden’ status code?
403
