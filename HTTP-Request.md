# HTTP Requests 

1. JavaScript is the language of the web because of its asynchronous capabilities. A set of tools that are used together to take advantage of JavaScript's asynchronous capabilities is called AJAX, which stands for Asynchronous JavaScript and XML. 
2. There are four HTTP request methods, two of which are `GET` and `POST`. 
3. `GET` requests only request information from other sources. 
4. `POST` methods can introduce new information to other sources in addition to requesting it. 
5. `GET` requests can be written using an `XMLHttpRequest` object and vanilla JavaScript. 
6. `POST` requests can also be written using an `XMLHttpRequest` object and vanilla JavaScript. 
7. Writing `GET` and `POST` requests with `XHR` objects and vanilla JavaScript requires constructing the `XHR`object using `new`, setting the `responseType`, creating a function that will handle the response object, and opening and sending the request. 
8. Much of the boilerplate used to write `GET` and `POST`requests with `XHR` and vanilla JavaScript can be reduced by using the `$.ajax()` method from the jQuery library. 
9. jQuery provides other helper methods that can further reduce boilerplate such as `$.get()`, `$.post()`, and `$.getJSON()`. 
10. Determining how to correctly write the requests and how to properly implement them requires carefully reading the documentation of the API with which you're working.