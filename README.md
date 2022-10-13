# HTTP 1.1vsHTTP 2

What is HTTP ?

HTTP stands for hypertext transfer protocol & it is used in client-server communication.
By using HTTP user sends the request to the server & the server sends the response to the user.
Before sending the request and the response there is a TCP connection established between client & server. 


| HTTP 1.1      |     HTTP 2    |
| ------------- | ------------- |
| HTTP 1.1 - uses Hyper Text Transfer Protocol - created in 1997|
|There are several stages of development of HTTP but we will focus mainly on HTTP/1.1 which was created in 1997 |HTTP 2 - uses SPDY Protocol - Speedy (networking protocol) |
|There is a persistent connection which means several requests & responses are merged in a single connection. | HTTP/2 was created in 2015.|
|Following are the drawbacks that lead to the creation of HTTP/2:| HTTP/2 works on the binary framing layer instead of textual that converts all the messages in binary format.|
|The first problem is HTTP/1.1 transfer all the requests & responses in the plain text message form. | HTTP/2 works on fully multiplexed that is one TCP connection is used for multiple requests.|
|The second one is head of line blocking in which TCP connection is blocked all other requests until the response does not receive. |HTTP/2 uses HPACK which is used to split data from header, it compresses the header.|The server sends all the other files like CSS & JS without the request of the client using the PUSH frame.|
|               |              |




