Java Client-Server Chat and Echo Applications
This repository contains the source code for two distinct, console-based client-server applications written in Java. These projects serve as practical examples of socket programming, multithreading, and handling input/output streams for network communication.

Projects Included
This repository contains two independent projects:

Two-Way Chat Application (Server.java, Client.java)

A real-time, bi-directional command-line chat program.

It uses a multi-threaded approach to handle simultaneous reading and writing operations, allowing both the client and server to send messages at any time.

Multi-Client Echo Server (mserver.java, mclient.java)

A server capable of handling multiple client connections concurrently.

For each connected client, the server simply "echoes" back any message it receives.

Technologies Used
Java: Core programming language.

Java Networking (java.net): For socket and server-socket programming.

Java I/O (java.io): For handling data streams between the client and server.

Java Threads: For concurrent execution of reading and writing tasks.
