# Ownership in Rust

Ownership is Rust's way of managing memory safely.

## Example
```rust
fn main() {
    let s = String::from("hello");
    let s2 = s;
}
Practice

Create a string and transfer ownership to another variable.
