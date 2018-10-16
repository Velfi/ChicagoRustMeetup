# This October In Rust

## New Toys

* [Evcxr] - A REPL and Jupyter kernel for Rust.
* [web-sys] - Raw bindings to all web APIs! Is also future-compatible with upcoming Web
  Assembly changes that will "eventually unlock even-faster-than-JS DOM performance".

## Blog Posts and Articles

* [A crate I want: 2d graphics] - A blog post from Raph Levien talking about his desire to have a
  simple, cross-platform 2d graphics library to act as a foundation for building cross-platform
  GUI applications.
* [Who authors the most popuplar crates on crates.io?] - A blog post from Steve Klabnik breaking
  down some data on which crate authors have written the most popular crates.
* [Calls between JavaScript and WebAssembly are finally fast 🎉] - Lin Clark talks about how
  upcoming changes in Firefox will drastically improve the speed of calling between JS and WASM.


## Talks and Videos

* [Rust & WebAssembly] - Talk by Nick Fitzgerald about the current state of using WebAssembly
  with Rust. He also digs into some of the details of how we interoperate between Rust/WASM
  and JavaScript.
* [A Tale of Two Asyncs] - Talk by Ashley Williams comparing and contrasting Rust and JavaScript,
  with a specific focus on the approaches both languages take to async programming.

[Evcxr]: https://www.reddit.com/r/rust/comments/9irjm7/evcxr_a_repl_and_jupyter_kernel_for_rust/
[web-sys]: https://rustwasm.github.io/2018/09/26/announcing-web-sys.html
[Rust & WebAssembly]: https://youtu.be/ZiiTRxWk8gA
[A Tale of Two Asyncs]: https://youtu.be/IEZb2WTzuro
[A crate I want: 2d graphics]: https://raphlinus.github.io/rust/graphics/2018/10/11/2d-graphics.html
[Who authors the most popuplar crates on crates.io?]: https://words.steveklabnik.com/who-authors-the-most-popular-crates-on-crates-io
[Calls between JavaScript and WebAssembly are finally fast 🎉]: https://hacks.mozilla.org/2018/10/calls-between-javascript-and-webassembly-are-finally-fast-%f0%9f%8e%89/
