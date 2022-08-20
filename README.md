# Setup Instructions
## Install rust
```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

## Install WASM target and trunk
```bash
rustup target add wasm32-unknown-unknown
cargo install trunk
```

## Run the application
```bash
trunk serve
```