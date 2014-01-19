# Hello

A 'hello world' package for Rust.

## Installation

You can install `hello` with `rustpkg`:

```
$ rustpkg install github.com/dskecse/hello
```

## Usage

Here's a simple program using `hello`:

```rust
extern mod hello;

fn main() {
    hello::world();
}
```

Suppose, you put that into a file called `hello.rs`, you can:

```
$ rustc hello.rs && ./hello
```

## License

Package is released under [MIT License](http://www.opensource.org/licenses/MIT).
