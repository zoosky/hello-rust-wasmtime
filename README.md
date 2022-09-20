# README

```bash
# build
cargo build --target wasm32-wasi

# install
curl https://wasmtime.dev/install.sh -sSf | bash

# run
wasmtime target/wasm32-wasi/debug/hello-world-rust.wasm

```
