# trexio

Standalone Rust bindings for the [TREXIO C library](https://github.com/trex-coe/trexio). This crate lives in its own independent repository.

![tests](https://github.com/trex-coe/trexio-rs/workflows/ci.yml/badge.svg)
![crates-io](https://img.shields.io/crates/v/trexio)

## Installation

This crate needs the TREXIO C library (libtrexio) and its headers on the system. See the [TREXIO installation instructions](https://github.com/trex-coe/trexio#installation) for details. Once installed, add this to your `Cargo.toml`:

```toml
[dependencies]
trexio = "2.6.101"
```

> **Version convention:** Rust crate versions in the `2.6.1xx` range correspond to C library version `2.6.x`. For example, crate `2.6.100` through `2.6.199` all target C library `2.6.1`, with the last two digits indicating the Rust-specific patch release.

## Documentation

- [TREXIO Documentation](https://trex-coe.github.io/trexio/)
- [Rust API Reference (docs.rs)](https://docs.rs/trexio/latest/trexio/)

