# miniupnp-rs

**ignore this please!**

[`miniupnp`](https://github.com/miniupnp/miniupnp) for Rust

wanted to play with making a simple Rust binding to `minipnpc` for Peach Cloud.

but now realize we should just use `upnpc` program, as it has features not included in exported library headers.

## how to play

https://rust-lang.github.io/rust-bindgen/requirements.html

```shell
apt-get install llvm-3.9-dev libclang-3.9-dev clang-3.9
```

clone repo

```shell
cargo build
cargo test
```

## references

- https://pavelfatin.com/access-your-raspberry-pi-from-anywhere/
- https://doc.rust-lang.org/cargo/reference/build-scripts.html
- https://rust-lang.github.io/rust-bindgen
- https://github.com/rust-lang/git2-rs/tree/master/libgit2-sys
