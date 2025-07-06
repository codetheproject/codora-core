# Codora Core

**Codora Core** is a foundational abstraction layer for Rust, designed to accelerate development by providing a suite of ergonomic utilities, macros, and helpers.

This crate is optional and can be included in your project by enabling the appropriate feature flags when adding `codora` as a dependency.

## Features

- Simplifies common Rust patterns and boilerplate
- Provides utility macros for error handling, string manipulation, concurrency, and more
- Aims to improve productivity and code clarity for Rust developers

## Usage

To use Codora Core, add it to your `Cargo.toml` with the desired features enabled:

 ```toml
 codora = { version = "x.y.z", features = ["core"] }
```

Then import and use the provided abstractions in your code as needed.

## Note

Codora Core is designed to be non-intrusive and fully compatible with standard Rust development practices. All abstractions are optional and can be adopted incrementally.
