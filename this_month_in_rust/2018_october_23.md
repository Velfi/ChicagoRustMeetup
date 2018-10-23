# This October In Rust

## Rust Updates

* [Rust 1.29.1] - Fixes a security vulnerability in `str::repeat`.
* [Rust 1.29.2] - Fixes a miscompilation bug coming from LLVM, and restores the rls-preview
  component for Windows GNU users.

Run `rustup update stable` to update to the latest version of Rust!

## Announcements

* [Announcing the Tokio Doc Push (we need you!)] - Tokio has a reputation for being hard to
  understand. In an effort to fix this and make it easier for everyone looking to use Tokio,
  the Tokio dev team is running the Tokio Doc Push! Come help out by writing some guides,
  tutorials, and code docs.
* [Announcing the xi-editor github organization] - Raph Levien has moved development of Xi
  into its own organization on GitHub, which means you no longer need to sign the Google
  Contributor License Agreement to make contributions! It also signals a shift towards Xi
  being owned primarily by the community.
* [docs.rs is now part of the rust-lang-nursery organization!] - The most popular way of reading
  crate docs is now officially supported by the docs team!
* [Update on the October 15, 2018 incident on crates.io] - Report from the crates.io team on a
  recent incident where someone was impersonating the crates.io team and uploading a large number
  of packages with common names.

## New Toys

* [Evcxr] - A REPL and Jupyter kernel for Rust.
* [web-sys] - Raw bindings to all web APIs! Is also future-compatible with upcoming Web
  Assembly changes that will "eventually unlock even-faster-than-JS DOM performance".
* [Bluetooth Low Energy with Rust] - Article announcing some new crates for doing BLE in Rust.
* [GLSL quasiquoting in Rust!] - Support for using quasiquoting to write GLSL shaders added
  to the [glsl] crate.
* [Introducing Ruukh Framework] - WebAssebly-first front-end framework for Rust inspired by
  [VueJS] and [ReactJS].
* [Shifgrethor] ([part 1], [part 2]) - A straight up actual garbage collector for Rust.
* [concread] - A new crate for concurrently readable datastructures.
* [macro_railroad browser plugin] - A cool browser plugin for visualizing macro syntax in Rust docs.
* [Rust on Glitch.com] - A basic example of how to run a Rust web app on [Glitch.com].

## Blog Posts and Articles

* [A crate I want: 2d graphics] - A blog post from Raph Levien talking about his desire to have a
  simple, cross-platform 2d graphics library to act as a foundation for building cross-platform
  GUI applications.
* [Who authors the most popuplar crates on crates.io?] - A blog post from Steve Klabnik breaking
  down some data on which crate authors have written the most popular crates.
* [Calls between JavaScript and WebAssembly are finally fast 🎉] - Lin Clark talks about how
  upcoming changes in Firefox will drastically improve the speed of calling between JS and WASM.
* [Continued progress porting Emacs to Rust] - Progress update on the [Remacs] project, which is
  an effort to port the core of Emacs to Rust.
* [Declarative Rust static analysis] - Interactive explanation of [comacro], an experimental tool
  for building things like clippy lints and other static analysis for Rust.
* [lolbench: automagically and empirically discovering Rust performance regressions]
* [Rust and JavaScript Interop ↔️]: Fairly deep dive into the inner workings of [wasm-bindgen] and
  how it creates the bindings between Rust-generated WebAssembly and JavaScript.
* [Rust can be difficult to learn and frustrating, but it’s also the most exciting thing in
  software development in a long time] - A poorly named article about one developer's experience
  gettings started with Rust. The name really says it all.
* [Towards fearless SIMD] - Blog post from Raph Levien talking about his goals for a user-friendly
  SIMD library.
* [Rust and the Three Laws of Informatics] - An article talking about how Rust balances and
  prioritizes correctness, maintainability, and performance.
* [Serverless Rust with AWS Lambda and WebAssembly] - Shows how to run Rust code on AWS Lambda
  by compiling it to WebAssembly and running it within Node.
* [Routing and Extraction in Tide: a first sketch] - Some implementation details about the Rising
  Tide effort.

## Talks and Videos

* [Rust & WebAssembly] - Talk by Nick Fitzgerald about the current state of using WebAssembly
  with Rust. He also digs into some of the details of how we interoperate between Rust/WASM
  and JavaScript.
* [A Tale of Two Asyncs] - Talk by Ashley Williams comparing and contrasting Rust and JavaScript,
  with a specific focus on the approaches both languages take to async programming.
* [Rust on the Edge] ([article][cloudflare]) - A presentation about using Rust for serverless web apps on CloudFlare.

[Evcxr]: https://www.reddit.com/r/rust/comments/9irjm7/evcxr_a_repl_and_jupyter_kernel_for_rust/
[web-sys]: https://rustwasm.github.io/2018/09/26/announcing-web-sys.html
[Rust & WebAssembly]: https://youtu.be/ZiiTRxWk8gA
[A Tale of Two Asyncs]: https://youtu.be/IEZb2WTzuro
[A crate I want: 2d graphics]: https://raphlinus.github.io/rust/graphics/2018/10/11/2d-graphics.html
[Who authors the most popuplar crates on crates.io?]: https://words.steveklabnik.com/who-authors-the-most-popular-crates-on-crates-io
[Calls between JavaScript and WebAssembly are finally fast 🎉]: https://hacks.mozilla.org/2018/10/calls-between-javascript-and-webassembly-are-finally-fast-%f0%9f%8e%89/
[Bluetooth Low Energy with Rust]: https://219design.com/bluetooth-low-energy-with-rust/
[Rust 1.29.1]: https://blog.rust-lang.org/2018/09/25/Rust-1.29.1.html
[Rust 1.29.2]: https://blog.rust-lang.org/2018/10/12/Rust-1.29.2.html
[Continued progress porting Emacs to Rust]: http://db48x.net/rust-remacs-2018/
[Remacs]: https://github.com/wilfred/remacs
[Declarative Rust static analysis]: http://blog.lambdaverse.org/comacro/
[comacro]: https://github.com/kazcw/comacro
[GLSL quasiquoting in Rust!]: https://phaazon.net/blog/glsl-quasiquoting
[glsl]: https://crates.io/crates/glsl
[Introducing Ruukh Framework]: https://sharadchand.com/2018/10/03/ruukh-framework.html
[VueJS]: https://vuejs.org/
[ReactJS]: https://reactjs.org/
[Announcing the Tokio Doc Push (we need you!)]: https://tokio.rs/blog/2018-10-doc-blitz/
[Announcing the xi-editor github organization]: https://raphlinus.github.io/xi/2018/10/01/xi-organization.html
[lolbench: automagically and empirically discovering Rust performance regressions]: https://blog.anp.lol/rust/2018/09/29/lolbench/
[Rust and JavaScript Interop ↔️]: https://blog.ryanlevick.com/posts/wasm-bindgen-interop/
[wasm-bindgen]: https://github.com/rustwasm/wasm-bindgen
[Rust can be difficult to learn and frustrating, but it’s also the most exciting thing in software development in a long time]: https://www.influxdata.com/blog/rust-can-be-difficult-to-learn-and-frustrating-but-its-also-the-most-exciting-thing-in-software-development-in-a-long-time/
[Shifgrethor]: https://github.com/withoutboats/shifgrethor
[part 1]: https://boats.gitlab.io/blog/post/shifgrethor-i/
[part 2]: https://boats.gitlab.io/blog/post/shifgrethor-ii/
[docs.rs is now part of the rust-lang-nursery organization!]: https://www.reddit.com/r/rust/comments/9q41wv/
[concread]: https://crates.io/crates/concread
[macro_railroad browser plugin]: https://www.reddit.com/r/rust/comments/9pnk1w/
[Towards fearless SIMD]: https://raphlinus.github.io/rust/simd/2018/10/19/fearless-simd.html
[Update on the October 15, 2018 incident on crates.io]: https://blog.rust-lang.org/2018/10/19/Update-on-crates.io-incident.html
[Rust on the Edge]: https://watch.cloudflarestream.com/15aa8c6340d40ac36db51c8455d08d2d
[cloudflare]: https://blog.cloudflare.com/cloudflare-workers-as-a-serverless-rust-platform/
[Rust and the Three Laws of Informatics]: https://blog.usejournal.com/rust-and-the-three-laws-of-informatics-4324062b322b
[Serverless Rust with AWS Lambda and WebAssembly]: https://blog.scottlogic.com/2018/10/18/serverless-rust.html
[Rust on Glitch.com]: https://glitch.com/edit/#!/hello-rust?path=README.md:1:0
[Glitch.com]: https://glitch.com/
[Routing and Extraction in Tide: a first sketch]: https://rust-lang-nursery.github.io/wg-net/2018/10/16/tide-routing.html
