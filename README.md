# HTTP 1.1vsHTTP 2

## What is HTTP ?

HTTP stands for hypertext transfer protocol & it is used in client-server communication.
By using HTTP user sends the request to the server & the server sends the response to the user.
Before sending the request and the response there is a TCP connection established between client & server. 


| HTTP 1.1      |     HTTP 2    |
| ------------- | ------------- |
| HTTP 1.1 - uses Hyper Text Transfer Protocol - created in 1997|HTTP 2 - uses SPDY Protocol - Speedy (networking protocol) 
|There are several stages of development of HTTP but we will focus mainly on HTTP/1.1 which was created in 1997 ||
|There is a persistent connection which means several requests & responses are merged in a single connection. | HTTP/2 was created in 2015.|
|Following are the drawbacks that lead to the creation of HTTP/2:| HTTP/2 works on the binary framing layer instead of textual that converts all the messages in binary format.|
|The first problem is HTTP/1.1 transfer all the requests & responses in the plain text message form. | HTTP/2 works on fully multiplexed that is one TCP connection is used for multiple requests.|
|The second one is head of line blocking in which TCP connection is blocked all other requests until the response does not receive. |HTTP/2 uses HPACK which is used to split data from header, it compresses the header.|The server sends all the other files like CSS & JS without the request of the client using the PUSH frame.|
|               |              |



# Objects And Its Internal Representation In JavaScript

1. Objects, in JavaScript, is it’s most important data-type and forms the important building blocks for modern JavaScript. 
2. objects in JavaScript may be defined as an unordered collection of related data, of primitive or reference types, in the form of “key: value” pairs. 
3. These keys can be variables or functions and are called properties and methods, respectively, in the context of an object.  
4.  Variable == properties ,  functions == methods in the context of a object
5. Objects are entirely different from the primitive data-types ( ex. string, Number, boolean, null, symbol and undefined )
6. These primitive data-types all store a single value each (depending on their types).
7. Objects are more complex and each object may contain any combination of these primitive data-types as well as reference data-types.
8. An object, is a reference data type.
9. Variables that are assigned a reference value are given a reference or a pointer to that value.
10. That reference or pointer points to the location in memory where the object is stored. 
11. Propertices of an object can be called using Object.properties
12. Methods of an object can be called using Object.Method
13. Example: 

var person = new Object();<br>
person.firstName = “Maharani”;<br>
person.lastName = “Jeyaraman”;<br>
person.age = 15;<br>
person.eyeColor = “blue”;<br>


