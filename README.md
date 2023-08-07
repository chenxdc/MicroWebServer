# MicroWebServer
Lightweight C++ Web Server for Linux

This is a Linux C++ Web server with efficient concurrency, incorporating a thread pool, non-blocking sockets, epoll (ET and LT), and event handling (Reactor and simulated Proactor). HTTP request messages are parsed using state machines to support both GET and POST methods. Additionally, the server-side database access enables user registration, login, and retrieval of images and video files on the web side. Furthermore, a synchronous/asynchronous logging system is implemented to monitor and record the server's runtime status.
