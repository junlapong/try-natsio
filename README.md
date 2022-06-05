# try-natsio

## Installation

__Server__

```
go install github.com/nats-io/nats-server/v2@latest
```

__Client__

```
go install github.com/nats-io/natscli/nats@latest
```

## Start Server

```
nats-server
```

## Client

```
nats context save example --server nats://nats.example.net:4222 --description 'Example.Net Server'

nats context save local --server nats://localhost:4222 --description 'Local Host' --select
```

```
nats context ls
```

