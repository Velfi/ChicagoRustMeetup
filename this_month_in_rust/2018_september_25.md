# This September in Rust

## Events Zelda Took Note Of
* RustConf 2018 - Go watch it on Youtube: https://www.youtube.com/playlist?list=PL85XCvVPmGQi3tivxDDF1hrT9qr5hdMBZ
* Rust 2018 is in stable now. It encompasses many features you've already been using plus some cool new ones: https://rust-lang-nursery.github.io/edition-guide/rust-2018/index.html
* `NLL` fixes and improvements. This code doesn't compile in Rust 2015 but does compile in Rust 2018: https://play.integer32.com/?gist=df0ae0274a4ee3edaabf8cd960ee9071&version=beta&mode=debug&edition=2015
* RLS (Rust Language Server) has reached 1.0: It's not complete but it's good enough for most everyone to start using if they aren't already
* `Rustfmt` will be stabilizes "soon". This is contentious because it occasionally breaks things
    * Alex Crichton compiled Rustfmt to wasm and has a running demo: https://alexcrichton.github.io/rustfmt-wasm/
* Pinning API
* Experimental Use of smallvec in the standard library
* 1.29 brings `cargo fix` and `cargo clippy`
* `Iterator::flatten` is now stable
* Fixed security vulnerability in the standard library due to `str::repeat`
* Rustdoc will now show docs for trait implementors
* Webrender is running on nightly Firefox for Windows 10 users with Nvidia cards

## Good Reads

* **2019 Strategy for Rustc and the RLS** https://internals.rust-lang.org/t/2019-strategy-for-rustc-and-the-rls/8361
* **Calling C# natively from Rust.** https://medium.com/@chyyran/calling-c-natively-from-rust-1f92c506289d
* **Falling in love with Rust** http://dtrace.org/blogs/bmc/2018/09/18/falling-in-love-with-rust/
* **Learning Generics in Rust** https://tutorialedge.net/rust/learning-generics-in-rust/
* **My RustConf 2018 Closing Keynote** https://kyren.github.io/2018/09/14/rustconf-talk.html
* **Oxidizing sourmash: Python and FFI** https://blog.luizirber.org/2018/08/23/sourmash-rust/
* **Programming Servo: A generic “worker event-loop”** https://medium.com/programming-servo/programming-servo-a-generic-worker-event-loop-400a6f113a60
* **Rising Tide: building a modular web framework in the open** https://rust-lang-nursery.github.io/wg-net/2018/09/11/tide.html
* **You can’t “turn off the borrow checker” in Rust** https://words.steveklabnik.com/you-can-t-turn-off-the-borrow-checker-in-rust
* **Isomorphic Desktop Apps with Rust** https://speice.io/2018/09/isomorphic-apps.html
