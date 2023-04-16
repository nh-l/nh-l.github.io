---
layout: default
title: Getting Started
nav_order: 2
parent: Rust
---

# Getting Started

---

## Summary

* Install the latest stable version of Rust using rustup
* Update to a newer Rust version
* Open locally installed documentation
* Write and run a “Hello, world!” program using rustc directly
* Create and run a new project using the conventions of Cargo

---


```console
$ cargo check    // 실행파일 생성 없이 컴파일만
$ cargo build    // 컴파일 + 실행파일 생성
$ cargo run      // 컴파일 + 실행파일 생성 + 실행
```

```rust
fn main() {
    println!("Hello, world!");
}
```

!가 붙으면 매크로이다.
