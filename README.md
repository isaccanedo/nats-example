# Exemplo de NATS usando JNats

## Start Nats Server using Docker
- Start Nats Server using Docker
  ```
  docker run --name nats --rm -p 4222:4222 nats
  ```
- Connecting to NATS Server
  ```
  telnet localhost 4222
  ```
- Publishing a message to subject `com.isaccanedo`:
  ```
  PUB com.isaccanedo 5
  hello
  ```
