# This October In Rust

## News and Announcements

*  🎈🎉 [Announcing Rust 1.39.0](https://blog.rust-lang.org/2019/11/07/Rust-1.39.0.html). 🎉🎈

  * The `.await` is over, `async fn`s are here!
  * References to by-move bindings in `match` guards!
  * Attributes on function parameters!
  * Borrow check migration warnings are hard errors in Rust 2018!
  * More `const fn`s in the standard library!
  * ... and more!

* [A call for blogs 2020](https://blog.rust-lang.org/2019/10/29/A-call-for-blogs-2020.html) - Help decide the direction of Rust development in 2020! See posts from other people [on Twitter](https://twitter.com/search?q=%23rust2020).

* [Completing the transition to the new borrow checker](https://blog.rust-lang.org/2019/11/01/nll-hard-errors.html) - The new borrow checker introduced in the 2018 edition introduced some breakage by catching soundness issues that were previously allowed. So far these have been given as warnings, but they'll become hard errors in Rust 1.40.

## Helpful Articles

* [A closer look at Ownership in Rust](https://blog.thoughtram.io/ownership-in-rust/) - And informative look at the nitty-gritty details of how Rust ownership model works with respect to dealing with memory.
* [PSA: You probably didn't want `.into_iter().cloned()`](https://www.reddit.com/r/rust/comments/dp3s25/psa_you_probably_didnt_want_into_itercloned/)
* [Demystifying Asynchronous Rust](https://teh-cmc.github.io/rust-async/html) - A (short) book digging into the details about how asynchronous Rust works.


## Tales from Production

* [FastSpark: A New Fast Native Implementation of Spark from Scratch](https://medium.com/@rajasekar3eg/fastspark-a-new-fast-native-implementation-of-spark-from-scratch-368373a29a5c) - [Apache Spark](https://en.wikipedia.org/wiki/Apache_Spark) is a general-purpose cluster-computing framework, and apparently it goes way faster implemented in Rust compared to Java.
* [Programming Servo: the incredibly shrinking timer](https://medium.com/programming-servo/programming-servo-the-incredibly-shrinking-timer-7283ae2a2669) - A short story showing how a robust ecosystem can help you write less code and end up with better software.
*  [Comparing parallel Rust and C++](https://parallel-rust-cpp.github.io/) - A *very* in-depth look at writing and optimizing parallel code with Rust, and an insightful comparison between Rust and C++.
*  [Using type-level programming in Rust to make safer hardware abstractions](https://blog.auxon.io/2019/10/25/type-level-registers/) - Statically encoding application semantics for fun and profit!
*  [Experimental rewrite of a low-level system component of the Windows codebase](https://msrc-blog.microsoft.com/2019/11/07/using-rust-in-windows/) - Another update from the MSRC about their work on using Rust in Windows.

## Tools and Toys

*  [Announcing async-std 1.0](https://async.rs/blog/announcing-async-std-1-0/) - `async-std` is a port of Rust’s standard library to the async world.
*  [Futures 0.3 released (with async/await support)](https://github.com/rust-lang-nursery/futures-rs/releases/tag/0.3.0) - No more awkward `futures-preview` libraries!
*  [genawaiter](https://github.com/whatisaphone/genawaiter) - A crate to allow generators on stable Rust.