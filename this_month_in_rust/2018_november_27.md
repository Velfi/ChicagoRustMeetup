# This November In Rust

## Rust Updates

* [Announcing Rust 1.30] - Procedural macros, `use` for macros, module system improvements, and more!
* [Announcing Rust 1.30.1] - Fixes a broken progress bar in MSYS terminals on Windows.

[Announcing Rust 1.30]: https://blog.rust-lang.org/2018/10/25/Rust-1.30.0.html
[Announcing Rust 1.30.1]: https://blog.rust-lang.org/2018/11/08/Rust-1.30.1.html

## Announcements

* [A verified email address will be required to publish to crates.io starting on 2019-02-28][email]
* [As of November 1st 2018, Rust makes up about 6% of the Firefox codebase!][firefox]
* [Announcing Rust 2018 Beta release!]
* [The last two months in rustsim #1] - There's now a rustsim organization in charge of [nphysics], [ncollide], and [nalgebra]! Here's what they've been up to.

[email]: https://users.rust-lang.org/t/a-verified-email-address-will-be-required-to-publish-to-crates-io-starting-on-2019-02-28/22425
[firefox]: https://twitter.com/eroc/status/1061049330574884864?s=09
[Announcing Rust 2018 Beta release!]: https://internals.rust-lang.org/t/announcing-rust-2018-beta-release/8901
[The last two months in rustsim #1]: https://www.rustsim.org/blog/2018/11/01/this-month-in-rustsim/
[nphysics]: https://nphysics.org/
[ncollide]: https://ncollide.org/
[nalgebra]: https://nalgebra.org/

## New Toys

* [TabNine] - A smart autocompleter for all languages. Free for usage with Rust as a thank you to the Rust community!
* [SUPER 0.5.0 released!] - SUPER is an Android application analysis tool that tries to detect potential security vulnerabilities.
* [soup] - A web scraping crate inspired by the [Beautiful Soup] python library.
* [json_in_type] - A macro for super-fast serialization of Rust types to JSON.
* [Announcing Gotham 0.3] - Gotham is a web server framework for Rust.

[TabNine]: https://www.reddit.com/r/rust/comments/9uhc1x
[SUPER 0.5.0 released!]: https://superanalyzer.rocks/2018/11/03/super-0.5.0-release
[soup]: https://pwoolcoc.gitlab.io/soup/soup/index.html
[Beautiful Soup]: https://www.crummy.com/software/BeautifulSoup/
[json_in_type]: https://github.com/lovasoa/json_in_type
[Announcing Gotham 0.3]: https://gotham.rs/blog/release/2018/10/29/gotham-0.3.html

## Blog Posts and Articles

* [WebAssembly’s post-MVP future: A cartoon skill tree][wasm-skill-tree]
* [Rust has higher kinded types already... sort of][rust-has-hkt]
* [One Page Wasm] - Teeny-tiny examples of Rust in the web browser.
* [Compile Time Feature Flags in Rust] - A good article discussing all the ways in which you can toggle functionality at compile time.
* [Can you Drop it?] - An article looking at [`mem::drop`] and the implications of how it's implemented.
* [Build Your Own Shell using Rust] - Explains details of how a terminal shell works by walking through the implementation of a basic shell in Rust.
* [Stacked Borrows Implemented] - A deep dive into the implementation of the Stacked Borrows model of ownership in Rust.
* [Middleware in Tide] - The Tide project is now on GitHub! Also this article discusses the current design for handling middleware in a Tide server.
* [Running Rust natively in AWS Lambda and testing it locally][rust-on-lambda] - There's finally a way to run a native Rust application on AWS! And this article explains how!
* [Rust And Game Development] - An exploration of the current state of game development in Rust, as well as some ideas for how to improve the ecosystem going forward.
* [Things Rust doesn’t let you do] - An exploration of some safe things that the Rust borrow checker currently doesn't allow, as well as ways that the borrow checker could be improved to better support these cases in the future.
* [Generating Sudoku Boards pt. 3: Rust for WebAssembly][sodoku3] - A continuation of a series of articles on implementing a Soduku board generator, this time looking at the effort necessary to run the generator in the web browser using WebAssembly.
* [proc_macro_attribute Revisited] - Llogiq goes over what it took for him to update his crates [flamer] and [overflower] to use the newly-stabilized `proc_macro_attribute`.
* [Monadic do notation in Rust: Part I][do-notation] - An exploration of one potential approach to implementing a monadic do-notation for Rust.
* [After NLL: Moving from borrowed data and the sentinel pattern][after-nll]
* [Under the Hood: How Rust Helps Keep Kentik’s Performance on High][kentik]
* [Truly zero cost] - A look into just how ~magical~ Rust's zero-cost abstractions are.
* [How to speed up the Rust compiler in 2018: NLL edition][nll-fast]
* [MIR-based borrowck is almost here][borrowck]
* [On dealing with owning and borrowing in public interfaces][owning]
* [Higher-Order Functions in Rust]
* [Shifgrethor III: Rooting] - Another article discussing the Shifgrethor garbage collector.
* [Shifgrethor IV: Tracing] - Another article discussing the Shifgrethor garbage collector.
* [Anchored and Uniform Paths] - The last great question to answer for the 2018 edition!
* [My release checklist for Rust programs][release] - Releasing a new version of your Rust program? Checkout this checklist first and make sure you're not forgetting anything!
* [Following up on the 2d graphics in Rust discussion][2d-rust]
* [2d graphics in Rust discussion - A look at GPU memory management][gpu-mem]
* [Finding and fixing memory leaks in a Hyper application or 'How I Learned to Stop Worrying and Love the Allocator'][alloc]
* [Parsing logs 230x faster with Rust][logs] - RubyGems.org used Rust to parse tons of log data super fast!
* [Improving ndarray-csv: Goodbye failure, Hello Extension Traits][ndarray-csv]
* [Problems Scaling A Large Multi-Crate Rust Project][multi-crate] - An interesting look at one team's issues dealing with a large Rust codebase.
* [The Case For Macros] - Sometimes you *should* use macros.

[wasm-skill-tree]: https://hacks.mozilla.org/2018/10/webassemblys-post-mvp-future/
[rust-has-hkt]: https://joshlf.com/post/2018/10/18/rust-higher-kinded-types-already/
[One Page Wasm]: https://fitzgen.github.io/one-page-wasm/
[Compile Time Feature Flags in Rust]: https://www.worthe-it.co.za/programming/2018/11/18/compile-time-feature-flags-in-rust.html
[Can you Drop it?]: http://optimistictypes.com/can-you-drop-it/
[`mem::drop`]: https://doc.rust-lang.org/std/mem/fn.drop.html
[Build Your Own Shell using Rust]: https://www.joshmcguigan.com/blog/build-your-own-shell-rust/
[Stacked Borrows Implemented]: https://www.ralfj.de/blog/2018/11/16/stacked-borrows-implementation.html
[Middleware in Tide]: https://rust-lang-nursery.github.io/wg-net/2018/11/07/tide-middleware.html
[rust-on-lambda]: https://medium.com/@bernardo.belchior1/running-rust-natively-in-aws-lambda-and-testing-it-locally-57080421426d
[Rust And Game Development]: https://alexene.github.io/2018/11/15/Rust-and-game-development.html
[Things Rust doesn’t let you do]: https://medium.com/@GolDDranks/things-rust-doesnt-let-you-do-draft-f596a3c740a5
[sodoku3]: https://medium.com/@rossharrison/generating-sudoku-boards-pt-3-rust-for-webassembly-85bd7294c34a
[proc_macro_attribute Revisited]: https://llogiq.github.io/2018/11/10/proc-macro.html
[flamer]: https://crates.io/crates/flamer
[overflower]: https://crates.io/crates/overflower
[do-notation]: https://varkor.github.io/blog/2018/11/10/monadic-do-notation-in-rust-part-i.html
[after-nll]: http://smallcultfollowing.com/babysteps/blog/2018/11/10/after-nll-moving-from-borrowed-data-and-the-sentinel-pattern/
[kentik]: https://www.kentik.com/blog/under-the-hood-how-rust-helps-keep-kentik's-performance-on-high/
[Truly zero cost]: https://vorner.github.io/2018/11/11/truly-zero-cost.html
[nll-fast]: https://blog.mozilla.org/nnethercote/2018/11/06/how-to-speed-up-the-rust-compiler-in-2018-nll-edition/
[borrowck]: http://smallcultfollowing.com/babysteps/blog/2018/10/31/mir-based-borrowck-is-almost-here/
[owning]: https://phaazon.net/blog/on-owning-borrowing-pub-interface
[Higher-Order Functions in Rust]: https://dev.to/deciduously/higher-order-functions-in-rust-287h
[Shifgrethor III: Rooting]: https://boats.gitlab.io/blog/post/shifgrethor-iii/
[Shifgrethor IV: Tracing]: https://boats.gitlab.io/blog/post/shifgrethor-iv/
[Anchored and Uniform Paths]: https://boats.gitlab.io/blog/post/anchored-uniform/
[release]: https://dev.to/sharkdp/my-release-checklist-for-rust-programs-1m33
[2d-rust]: https://nical.github.io/posts/rust-2d-graphics-01.html
[gpu-mem]: https://nical.github.io/posts/rust-2d-graphics-02.html
[alloc]: https://blog.1aim.com/2018/10/finding-and-fixing-memory-leaks-in-a-hyper-application-or-how-i-learned-to-stop-worrying-and-love-the-allocator/
[logs]: https://andre.arko.net/2018/10/25/parsing-logs-230x-faster-with-rust/
[ndarray-csv]: https://paulkernfeld.com/2018/10/27/improving-ndarray-csv.html
[multi-crate]: https://robert.ocallahan.org/2018/10/problems-scaling-large-multi-crate-rust.html
[The Case For Macros]: https://llogiq.github.io/2018/10/25/macros.html
