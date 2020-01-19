# First Welcome from Islamabad
this is a demo rust library published on crates.io

to use this library you have to add following line in dependency section of cargo.toml

`islamabad = "0.1.0"`

your cargo.toml file should look like this:
```
[package]
name = "hello_world"
version = "0.1.0"
authors = ["imran82ali <code.imranali@gmail.com>"]
edition = "2018"

[dependencies]
islamabad = "0.1.0"
```

In `src/main.rs` you can use like this:

```
use islamabad;
fn main() {
    println!("Hello, world!");
    islamabad::welcome();
}
```
following will also work:
```
use islamabad::welcome;
fn main() {
    println!("Hello, world!");
    welcome();
    }
```

now `cargo run` for results
