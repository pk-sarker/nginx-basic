# nginx-basic
[Nginx](http://nginx.org/en/) is a special type of [proxy server](https://en.wikipedia.org/wiki/Proxy_server). A proxy server is an intermediary server that sits between servers or client and server. It receives request from a http client or a server and forward the request to desired server and receive response from desired server and pass the response to the requested server or to client. 
 
Nginx is a HTTP and [reserved proxy](https://en.wikipedia.org/wiki/Reverse_proxy) server that typically sits behind the firewall in a private network and directs client requests to the appropriate backend server or forward requests from one server to another server. Nginx also used as mail proxy server, a generic TCP/UDP proxy server.

# Table of Contents
* [Features](#features)



## Features
Nginx has whole lot of features. You can have a look at those features at Nginx site. Here we will see couple of features for which Nginx is commonly used.
  * Asynchronous event-driven approach is used to handling requests. Nginx's modular event-driven architecture can provide more predictable performance under high loads.
  * Load balancing. If you have multiple instances of same server then you can configure Nginx to balance load between those servers. 