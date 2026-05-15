# @net/hyper — HTTP Library for Zeta

Auto-converted from [hyper](https://crates.io/crates/hyper) v1.9.0 via [Dark Factory](https://github.com/murphsicles/dark-factory).

## Features
| Feature | Description |
|---------|-------------|
| **HTTP/1.1** | Full HTTP/1.1 client and server with keep-alive, pipelining, chunked transfer |
| **HTTP/2** | HTTP/2 with h2 multiplexing, flow control, server push |
| **Client** | Connection pooling, TLS (via rustls/ring), redirect following |
| **Server** | Graceful shutdown, connection limits, HTTP upgrade |
| **Body** | Streaming request/response bodies with size hints |
| **RT** | Configurable executor (tokio, async-std, custom) |

## Dependency chain
hyper → tower → tokio-util → tokio → futures

## Stats: ~15,000 lines, 0 unsupported items

## License
MIT