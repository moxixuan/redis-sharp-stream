# redis-sharp-stream
a simple to implement redis stream by charp

why?

i need Message queue (like RabbitMQ) or Kafka, it only depend on redis.

##why not [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis/PipelinesMultiplexers)?

it is a nice job. but the not support block read.

##why not [cap](https://github.com/dotnetcore/CAP)?

cap also supply redis stream. but it depend on sqlserver. it disable to fan out messages to multiple clients.


https://redis.io/topics/streams-intro
