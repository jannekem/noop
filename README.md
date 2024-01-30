# Noop: Your Go-To No-Operation Application

Welcome to Noop, a versatile and lightweight no-operation executable designed to do nothing. Noop is built to accept any arguments you throw at it, and it will always exit with success.

Whether you're testing command line scripts, orchestrating complex workflows, or just need a placeholder executable, Noop is your reliable companion. It's like a black hole for commands - everything goes in, nothing comes out, but it always ends in success.

With Noop, you can focus on building and testing your actual application logic without worrying about side effects from placeholder executables. It's the silent partner you didn't know you needed.

Start using Noop today and experience the peace of mind that comes with a truly no-operation executable.

## Installation

Noop is available as a pre-built binary for Linux, macOS, and Windows. You can download the latest release suitable for your system from the [GitHub releases page](https://github.com/jannekem/noop/releases). The binary is a standalone executable with no dependencies and can be renamed to your preference.

Alternatively, you can build Noop from the source using the Rust compiler. The easiest way to install Rust is by using [rustup](https://rustup.rs/). Clone or download the source code from this repository and run `cargo build --release` to build the binary for your system. The resulting binary will be located in the `target/release` directory.

If you require Noop to be available system-wide, you can copy the binary to a directory included in your system path. Rust's Cargo package manager also provides a convenient way to install the binary globally:

```
cargo install --git https://github.com/jannekem/noop
```

## Usage

Using Noop is as simple as it gets. Once you've obtained the binary, you can call it from the command line with any arguments. Here's an example:

```powershell
noop.exe arg1 arg2 arg3
```

## License

Noop is licensed under the Apache License, Version 2.0. See [LICENSE](LICENSE) for the full license text.
