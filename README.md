# client-server

## Requirements
You are required to create two console applications using C++: 1. client 2. server; with the following features:

The client should be able to connect to the server through a NamedPipe
The client should be able to make both sync and async calls to the server
The client should be able to send trivial data (strings, numbers) to the server
The client should be able to create objects on the server (based on req-7 below), retrieve them, their attributes and call methods on them
The server should be able to receive both sync/async connection requests from clients
The server should be able to store data provided by the client via NamedPipe in a reasonable data structure
The server should be able to register a custom class (w/ related functions, attributes) which can be used by the client (see req-4)
The server should be able to store the custom objects created by the client for the custom class created in req-7
