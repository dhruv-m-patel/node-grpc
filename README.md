# node-grpc

A basic example of node-grpc implementation

## PREREQUISITES

- `node`: This requires Node 0.12.x or greater.

## INSTALL

```sh
$ # Get the gRPC repository
$ git clone git@github.com/dhruv-m-patel/node-grpc
$ cd node-grpc
$ npm install
```

## TRY IT!

There are two ways to generate the code needed to work with protocol buffers in Node.js - one approach uses [Protobuf.js](https://github.com/dcodeIO/ProtoBuf.js/) to dynamically generate the code at runtime, the other uses code statically generated using the protocol buffer compiler `protoc`. The examples behave identically, and either server can be used with either client.

- Run the server

  ```sh
  $ npm run dynamic:server
  $ # OR
  $ npm run static:server
  ```

- Run the client

  ```sh
  $ npm run dynamic:client
  $ # OR
  $ npm run static:client
  ```

[grpc basics: node.js]: https://grpc.io/docs/languages/node/basics

For comprehensive documentation, including an [Introduction to gRPC][intro] and
tutorials that use this example code, visit [grpc.io](https://grpc.io).

For a complete list of supported languages, see [Supported languages][lang].

[intro]: https://grpc.io/docs/what-is-grpc/introduction
[lang]: https://grpc.io/docs/languages/
