# Spring_Fourth_App
REST API
In that project I use REST functionality that's why I don’t use .xml.
Partially I copied some files from my privious object “Spring_Profile” which is my third Spring app, such as dao, entity and service.
For communication between client and server (Tomcat) here will be used Postman like a Client side.

From the client(Postman) sended  request “api/employees” by POST method, in body of it will be JSON.
It will get some benefits - not only HTTP requests with get method, but also other methods, as a post method,
and it will give more information from requests and responses

But in the end I added an application with the same functionality as Postman had (for my needs).
So, after all manipulations, from this "Client" application, using the REST API, it  contacts to (communicates with)
REST service via HTTP request, and after the result of this request, an HTTP response will be received.
