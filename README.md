# play-scala-websocket-example-enhancement

This is an example Play application that is forked from https://github.com/playframework/play-samples/tree/2.8.x/play-scala-websocket-example (all credits of base-Play-framework goes to the developers who contributed to Play's open-source code).

This project shows how to use Play's Websocket API in Scala, by showing a series of stock tickers updated using WebSocket. The Websocket API is built on Akka Streams (so is async, non-blocking, and backpressure aware).

In addition, this project tries to do the following enhancements:
* User should be able to add/remove stocks to watch
* Stock Quotes must be real prices retrieved in realtime (not generated prices)


## How to run this Project (Locally):

* pull down this Git Repository
* run `sbt clean compile`
* run `sbt run`
* go to "http://localhost:9000" (make sure Port 9000 is available first)

## TODOs for this Project:

The Reactive Stocks example combines Reactive Push, Reactive Requests, Reactive Composition, and a Reactive UI to create a Resilient, Interactive, Scalable, and Event-Driven application.  For more information, please see the documentation for Websockets and Akka Streams:

* Refactor code to remove stock(s) correctly
* Refactor code to retrieve Stock Prices in realtime (currently - Stock Prices are simulated)
* Add more Scala Unit Tests
