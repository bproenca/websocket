# Intro Spring WebSocket

https://www.baeldung.com/websockets-spring

WebSockets is a bi-directional, full-duplex, persistent connection between a web browser and a server. Once a WebSocket connection is established the connection stays open until the client or server decides to close this connection.

## Run the project
```
./mvnw spring-boot:run
```

### SockJS

SockJS is a browser JavaScript library that provides a WebSocket-like object. SockJS gives you a coherent, cross-browser, Javascript API which creates a low latency, full duplex, cross-domain communication channel between the browser and the web server.

Under the hood SockJS tries to use native WebSockets first. If that fails it can use a variety of browser-specific transport protocols and presents them through WebSocket-like abstractions.

SockJS is intended to work for all modern browsers and in environments which don't support the WebSocket protocol -- for example, behind restrictive corporate proxies.

https://github.com/sockjs/sockjs-client

### STOMP

STOMP is a simple interoperable protocol designed for asynchronous message passing between clients via mediating servers. It defines a text based wire-format for messages passed between these clients and servers.

STOMP has been in active use for several years and is supported by many message brokers and client libraries. 

https://stomp.github.io/stomp-specification-1.2.html#Abstract