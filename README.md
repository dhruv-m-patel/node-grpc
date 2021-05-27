# node-grpc

A basic example of node-grpc implementation

## Setup

```sh
$ git clone git@github.com/dhruv-m-patel/node-grpc
$ cd node-grpc
$ npm install
```

## Examples

### Dynamic Server and Client

```sh
$ npm run dynamic:server
$ # and in another terminal
$ npm run dynamic:client
```

### Static Server and Client

```sh
$ npm run static:server
$ # And in another terminal
$ npm run static:client
```

### Dynamic Route Server and Client (With Streaming RPC)

```sh
$ npm run dynamic:routes:server
$ # and in another terminal
$ npm run dynamic:routes:client
```

[grpc basics: node.js]: [basics]

For comprehensive documentation, including an [Introduction to gRPC][intro] and
tutorials that use this example code, visit [grpc.io]

For a complete list of supported languages, see [Supported languages][lang].

[intro]: https://grpc.io/docs/what-is-grpc/introduction
[lang]: https://grpc.io/docs/languages/
[basics]: https://grpc.io/docs/languages/node/basics
[grpc.io]: https://grpc.io
