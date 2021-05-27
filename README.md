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

### Dynamic Route Server and Client

```sh
$ npm run dynamic:routes:server
$ # and in another terminal
$ npm run dynamic:routes:client
```

[grpc basics: node.js]: https://grpc.io/docs/languages/node/basics

For comprehensive documentation, including an [Introduction to gRPC][intro] and
tutorials that use this example code, visit [grpc.io](https://grpc.io).

For a complete list of supported languages, see [Supported languages][lang].

[intro]: https://grpc.io/docs/what-is-grpc/introduction
[lang]: https://grpc.io/docs/languages/
