# wasmedge-barcoder

This demo runs an echo server on localhost, it will detech barcode in HTTP request.

## Build

```bash
cargo build --target wasm32-wasi --release
```

## Run

```bash
wasmedge ./target/wasm32-wasi/release/wasmedge-bardecoder.wasm
```
