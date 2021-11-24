# wasmedge-barcoder

This demo runs an echo server on localhost.

## Build

```bash
cargo build --target wasm32-wasi --release
```

## Run

```bash
wasmedge ./target/wasm32-wasi/release/wasmedge-bardecoder.wasm
```
