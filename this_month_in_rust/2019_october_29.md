# This October In Rust

## News and Announcements

* 🎈🎉 [Announcing Rust 1.38.0](https://blog.rust-lang.org/2019/09/26/Rust-1.38.0.html). 🎉🎈
  * Pipelined compilation!
  * Linting incorrect usage of `mem::uninitialized` and `mem::zeroed`!
  * Mark macros `#[deprecated]`!
  * Use `std::any::type_name` for a debug-only way to get the name of a type!
  * ... and more!
* [Announcing Rustup 1.20.0](https://blog.rust-lang.org/2019/10/15/Rustup-1.20.0.html)
  * Support for different install profiles.
  * Only install latest compatible nightly.
  * Improvements to `rustup doc`.
* [Security advisory for Cargo](https://blog.rust-lang.org/2019/09/30/Security-advisory-for-cargo.html) - Rust 1.0 - 1.25 are vulnerable to malicious crate name squatting that exploits a newer Cargo feature not present in those older versions. If you're using this version of Rust, update to the latest version to avoid this issue!
* [`async`/`await` hits beta!](https://blog.rust-lang.org/2019/09/30/Async-await-hits-beta.html)
* [Announcing the "Inside Rust" Blog](https://blog.rust-lang.org/inside-rust/index.html) - A new blog with more regular updates on the internal goings-on in Rust's development.

## Helpful Articles

* [Accurate mental model for Rust's reference types](https://docs.rs/dtolnay/0.0.6/dtolnay/macro._02__reference_types.html) - Discusses how it's more accurate to look at `&T` and `&mut T` in terms of sharing rather than mutability, despite the way that the types are named.
* [My favorite Rust function](https://blog.jabid.in/2019/10/11/drop.html) - Ever wondered how `mem::drop` is implemented?
* [Debugging Rust code in CLion](https://blog.jetbrains.com/clion/2019/10/debugging-rust-code-in-clion/)
* [The node experiment - exploring async basics with Rust](https://cfsamson.github.io/book-exploring-async-basics/) - Curious about what "async" is and how it works? Got lots of time on your hands? This is a deep dive into the topic for those who really want to understand it better.
* [Migrating a crate from futures 0.1 to 0.3](https://www.ncameron.org/blog/migrating-a-crate-from-futures-0-1-to-0-3/)

## Tales from Production

* [Causal Profiling Rust Code](https://llogiq.github.io/2019/09/25/coz.html) - Causal profiling is a relatively new technique for profiling how optimzations impact an application's runtime as a whole.
* [Designing a COM library for Rust](https://msrc-blog.microsoft.com/2019/10/08/designing-a-com-library-for-rust/) - Another update from the MSRC on using Rust for secure systems-level software development.
* [Making the Tokio scheduler 10x faster](https://tokio.rs/blog/2019-10-scheduler/) - A super interesting look into some recent optimizations to the Tokio runtime.

## Tools and Toys

* [tonic](https://github.com/hyperium/tonic) - gRPC client & server implementation with async/await support.
* [reqwest alpha.await](https://seanmonstar.com/post/188220739932/reqwest-alphaawait)
* [Static Assertions 1.0](https://nikolaivazquez.com/posts/programming/rust-static-assertions-1_0/)
* [A Tiny, Static, Full-Text Search Engine using Rust and WebAssembly](https://endler.dev/2019/tinysearch/)
