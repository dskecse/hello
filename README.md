# Hello

A 'hello world' package for Rust.

## Installation

To depend on a library, add it to your `Cargo.toml` and run:

    $ cargo update

Pull in that library using `extern crate` in your `main.rs`.

## Usage

Here's a simple program using `hello`:

```rust
extern crate hello;

fn main() {
    hello::world();
}
```

You can simply run it with:

    $ cargo run

## License

Package is released under [MIT License](http://www.opensource.org/licenses/MIT).
