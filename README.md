Centrifugo is an open-source scalable real-time messaging server. Centrifugo can instantly deliver messages to application online users connected over supported transports (WebSocket, HTTP-streaming, SSE/EventSource, GRPC, SockJS, WebTransport). Centrifugo has the concept of a channel – so it's a user-facing PUB/SUB server.

Centrifugo is language-agnostic and can be used to build chat apps, live comments, multiplayer games, real-time data visualizations, collaborative tools, etc. in combination with any backend. It is well suited for modern architectures and allows decoupling the business logic from the real-time transport layer.

Several official client SDKs for browser and mobile development wrap the bidirectional protocol. In addition, Centrifugo supports a unidirectional approach for simple use cases with no SDK dependency.

## Documentation

* [Centrifugo official documentation site](https://centrifugal.dev)
* [Installation instructions](https://centrifugal.dev/docs/getting-started/installation)
* [Getting started tutorial](https://centrifugal.dev/docs/getting-started/quickstart)
* [Design overview and idiomatic usage](https://centrifugal.dev/docs/getting-started/design)
* [FAQ](https://centrifugal.dev/)

## Join community

* [Telegram](https://t.me/joinchat/ABFVWBE0AhkyyhREoaboXQ)
* [Discord](https://discord.gg/tYgADKx)
* [Twitter](https://twitter.com/centrifugal_dev)

## Why Centrifugo

The core idea of Centrifugo is quite simple – it's a PUB/SUB server on top of modern real-time transports:

![scheme](https://raw.githubusercontent.com/centrifugal/centrifugo/v2/docs/content/images/scheme_sketch.png)

The hard part is to make this concept production-ready, efficient and available from different application environments. Centrifugo is a mature solution that already helped many projects with adding real-time features. It provides unique properties not available in other OSS solutions in the area:

* Built-in scalability to many machines with Redis, KeyDB, Nats, Tarantool
* Simple HTTP and GRPC server API to communicate from the backend
* Flexible connection authentication mechanisms: JWT and proxy-like
* Different types of Subscriptions: client-side and server-side
* Hot message history in channels, with automatic message recovery upon reconnect
* Online channel presence information, with join/leave notifications
* A way to send RPC calls to the backend over the real-time connection
* Strict and effective client protocol wrapped by several official SDKs
* Variety of supported real-time transports, both JSON and binary Protobuf message transfer
* Beautiful embedded admin web UI
* And much more, visit [Centrifugo doc site](https://centrifugal.dev)

## Backing

This repository is hosted by [packagecloud.io](https://packagecloud.io/).

<a href="https://packagecloud.io/"><img height="46" width="158" alt="Private NPM registry and Maven, RPM, DEB, PyPi and RubyGem Repository · packagecloud" src="https://packagecloud.io/images/packagecloud-badge.png" /></a>

Also thanks to [JetBrains](https://www.jetbrains.com/) for supporting OSS (most of the code here written in Goland):

<a href="https://www.jetbrains.com/"><img height="140" src="https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.png" alt="JetBrains logo"></a>
