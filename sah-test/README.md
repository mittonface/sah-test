# Dragonball CLI

A command-line tool to query Dragonball character information from a Dragonball wiki API.

## Build Instructions

To build the project:

```bash
cargo build
```

For a release build:

```bash
cargo build --release
```

## Usage

```bash
cargo run -- <character_name>
```

Example:

```bash
cargo run -- "Goku"
```

## Testing

Run the test suite:

```bash
cargo nextest run --failure-output immediate --hide-progress-bar --status-level fail --final-status-level fail
```

If `cargo nextest` is not installed:

```bash
cargo install cargo-nextest
```

## Development

### Code Quality Checks

Run clippy for linting:

```bash
cargo clippy
```

Format code:

```bash
cargo fmt --all
```

Check formatting:

```bash
cargo fmt --all -- --check
```
