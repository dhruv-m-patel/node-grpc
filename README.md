# node-grpc

A basic example of node-grpc implementation

## Setup

```sh
$ git clone git@github.com/dhruv-m-patel/node-grpc
$ cd node-grpc
$ npm install
```

## Examples

### Dynamic Greeter

Prints greeting messages

```sh
$ npm run dynamic:greeter:server
$ # and in another terminal
$ npm run dynamic:greeter:client
```

### Static Greeter

Prints greeting messages

```sh
$ npm run static:greeter:server
$ # And in another terminal
$ npm run static:greeter:client
```

### Dynamic Routes Guide (With Streaming RPC)

Prints route guide messages

```sh
$ npm run dynamic:routes:server
$ # and in another terminal
$ npm run dynamic:routes:client
```

### Static Routes Guide (With Streaming RPC)

Prints route guide messages

```sh
$ npm run static:routes:server
$ # and in another terminal
$ npm run static:routes:client
```

## References

[grpc basics: node.js]: [basics]

For comprehensive documentation, including an [Introduction to gRPC][intro] and
tutorials that use this example code, visit [grpc.io]

For a complete list of supported languages, see [Supported languages][lang].

[intro]: https://grpc.io/docs/what-is-grpc/introduction
[lang]: https://grpc.io/docs/languages/
[basics]: https://grpc.io/docs/languages/node/basics
[grpc.io]: https://grpc.io
