# play-java-websocket-example

[![Travis](https://img.shields.io/travis/playframework/play-java-websocket-example.svg?style=flat)](https://travis-ci.org/playframework/play-java-websocket-example) [![GitHub issues](https://img.shields.io/github/issues/playframework/play-java-websocket-example.svg?style=flat)](https://github.com/playframework/play-java-websocket-example/issues) [![GitHub forks](https://img.shields.io/github/forks/playframework/play-java-websocket-example.svg?style=flat)](https://github.com/playframework/play-java-websocket-example/network) [![GitHub stars](https://img.shields.io/github/stars/playframework/play-java-websocket-example.svg?style=flat)](https://github.com/playframework/play-java-websocket-example/stargazers)

This is an example Play application that shows how to use Play's Websocket API in Java, by showing a series of stock tickers updated using WebSocket.

The Websocket API is built on Akka Streams, and so is async, non-blocking, and backpressure aware.  Using Akka Streams also means that interacting with Akka Actors is simple.

There are also tests showing how Junit and Akka Testkit are used to test actors and flows.

For more information, please see the documentation for Websockets and Akka Streams:

* https://www.playframework.com/documentation/latest/JavaWebSockets
* http://doc.akka.io/docs/akka/current/java/stream/stream-flows-and-basics.html#stream-materialization
* http://doc.akka.io/docs/akka/current/java/stream/stream-integrations.html#integrating-with-actors
