# Minimal Async Runtime

A minimal single-threaded async runtime implementation in Rust, built without external runtime dependencies.

## Features

- Spawn and execute async tasks with `spawn()`
- Async sleep functionality with `sleep(Duration)`
- Top-level async function execution via `block_on()`
- Simplified configuration using `mini_rt!` macro
- JoinHandle support for task results
- Cooperative task scheduling

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/Awungia112/async-runtime.git
cd async-runtime
```

2. Build the project:
```bash
cargo build
```

3. Run the example:
```bash
cargo run
```

The example will demonstrate the runtime's functionality by running two concurrent tasks with different sleep durations.

## Dependencies

- futures = "0.3"
- lazy_static = "1.4"

## License

MIT 