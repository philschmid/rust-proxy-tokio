# Rust Proxy using `Tokio.rs`, `Hyper` & `Axum`

This is an example project on how to build a HTTP Proxy using the `Tokio` stack with their new `Axum` crate. The idea is to proxy incoming request and be able to trace, authorize, log, measure and monitor the traffic.

## Resources

- [`Tokio`](https://tokio.rs)
- [Hyper http proxy](https://github.com/hyperium/hyper/blob/master/examples/http_proxy.rs)
- [hyper proxy crate](https://crates.io/crates/hyper-proxy)
- [medium blog post](https://medium.com/swlh/writing-a-proxy-in-rust-and-why-it-is-the-language-of-the-future-265d8bf7c6d2)
- [hyper reverse proxy crate](https://github.com/felipenoris/hyper-reverse-proxy)
- [`axum` example](https://github.com/tokio-rs/axum/blob/main/examples/http-proxy/src/main.rs)