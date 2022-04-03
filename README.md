# 'Zero To Production In Rust'
> Zero To Production is the ideal starting point for your journey as a Rust backend developer.
You will learn by doing: you will build a fully functional email newsletter API, starting from scratch.

Check out the free sample at [www.zero2prod.com](https://www.zero2prod.com/).

## Development commands

### Additional development tools
```bash
rustup component add clippy
rustup component add rustfmt
cargo install cargo-watch
cargo install cargo-tarpaulin
cargo install cargo-audit
cargo install cargo-edit
cargo install cargo-expand
```
### Linting
`cargo fmt`

### Formatting
`cargo clippy`

### Watch tests
`cargo watch -x check -x test -x run`

### Code coverage
`cargo tarpaulin --ignore-tests`

### Security audit
`cargo audit`