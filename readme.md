# refs

[Building a WebRTC video and audio Broadcaster in Golang using ION-SFU, and media devices](https://gabrieltanner.org/blog/broadcasting-ion-sfu)

## build and run

### ion-sfu

```sh
go build ./cmd/signal/json-rpc/main.go && ./main -c config.toml
```

### device client

```sh
go run main.go
```

### server

```sh
npm install
node server.js
```

### open web browser and access

```
http://localhost:3000/
```

