Detects whether a terminal supports unicode.

This crate is a Rust port mashing together
[@sindresorhus](https://github.com/sindresorhus)'
[`is-unicode-supported`](https://npm.im/is-unicode-supported) and
[@iarna](https://github.com/iarna)'s
[`has-unicode`](https://npm.im/has-unicode) NPM packages.

## Example

```rust
if supports_unicode::on(&std::io::stdout()) {
    println!("stdout supports unicode output");
} else {
    println!("no unicode, please");
}
```
