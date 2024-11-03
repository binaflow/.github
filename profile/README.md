# Binaflow

**Binaflow** is a WebSocket-based message exchange solution designed to facilitate efficient, structured communication between clients and servers using serialized protobuf messages. Inspired by REST API conventions, Binaflow supports a request-response pattern with message types and unique message IDs to enable organized, asynchronous communication.

Perfect for tasks where data transmission speed is crucial, such as games, trading tools, etc...

## Key Features

- **WebSocket Communication**: Establishes real-time, bidirectional communication between clients and servers.
- **Protocol Buffers (protobuf)**: Utilizes protobuf for serialization, ensuring compact and efficient data transmission.
- **Request-Response Pattern**: Adopts a request/response structure similar to REST APIs. Each message includes a message type and a unique message ID for tracking responses.

## Architecture

The Binaflow ecosystem consists of client and server implementations, designed to be both modular and scalable.

### Client (Browser)

- **JavaScript (Browser)**: [binaflow-js-client](https://github.com/binaflow/binaflow-js-client) – A JavaScript client for browser-based applications, providing seamless integration with Binaflow's WebSocket-based message exchange.

### Server

- **Java + Spring Boot**: [binaflow-spring-boot-starter](https://github.com/binaflow/binaflow-spring-boot-starter) – A Spring Boot starter package that simplifies server-side integration for Java-based backend services.
- **Node.js** (Coming Soon): Planned support for Node.js backend applications.

### Examples

[Example project](https://github.com/binaflow/examples) an application where message exchanging implemented with binaflow.
