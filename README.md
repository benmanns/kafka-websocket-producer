# kafka-websocket-producer
Consumes from a websocket and writes data to STDOUT. Pipe to [kafkacat](https://github.com/edenhill/kafkacat) to send to your Kafka cluster.

## Install

Install with

```sh
go get github.com/benmanns/kafka-websocket-producer/...
```

and run with

```sh
kafka-websocket-producer -url "wss://www.stockfighter.io/ob/api/ws/EXB123456/venues/TESTEX/tickertape"
```
