# This November In Rust

## Rust Updates

* [Announcing Rust 1.30.1]

[Announcing Rust 1.30.1]: https://blog.rust-lang.org/2018/11/08/Rust-1.30.1.html

## Announcements

* [A verified email address will be required to publish to crates.io starting on 2019-02-28][email]
* [As of November 1st 2018, Rust makes up about 6% of the Firefox codebase!][firefox]

[email]: https://users.rust-lang.org/t/a-verified-email-address-will-be-required-to-publish-to-crates-io-starting-on-2019-02-28/22425
[firefox]: https://twitter.com/eroc/status/1061049330574884864?s=09

## New Toys

## Blog Posts and Articles

* [Compile Time Feature Flags in Rust] - A good article discussing all the ways in which you can toggle functionality at compile time.
* [Can you Drop it?] - An article looking at [`mem::drop`] and the implications of how it's implemented.
* [Build Your Own Shell using Rust] - Explains details of how a terminal shell works by walking through the implementation of a basic shell in Rust.
* [Stacked Borrows Implemented] - A deep dive into the implementation of the Stacked Borrows model of ownership in Rust.
* [Middleware in Tide] - The Tide project is now on GitHub! Also this article discusses the current design for handling middleware in a Tide server.
* [Running Rust natively in AWS Lambda and testing it locally] - There's finally a way to run a native Rust application on AWS! And this article explains how!
* [Rust And Game Development] - An exploration of the current state of game development in Rust, as well as some ideas for how to improve the ecosystem going forward.
* [Things Rust doesn’t let you do] - An exploration of some safe things that the Rust borrow checker currently doesn't allow, as well as ways that the borrow checker could be improved to better support these cases in the future.
* [Generating Sudoku Boards pt. 3: Rust for WebAssembly] - A continuation of a series of articles on implementing a Soduku board generator, this time looking at the effort necessary to run the generator in the web browser using WebAssembly.
* [proc_macro_attribute Revisited] - Llogiq goes over what it took for him to update his crates [flamer] and [overflower] to use the newly-stabilized `proc_macro_attribute`.
* [Monadic do notation in Rust: Part I] - An exploration of one potential approach to implementing a monadic do-notation for Rust.

[Compile Time Feature Flags in Rust]: https://www.worthe-it.co.za/programming/2018/11/18/compile-time-feature-flags-in-rust.html
[Can you Drop it?]: http://optimistictypes.com/can-you-drop-it/
[`mem::drop`]: https://doc.rust-lang.org/std/mem/fn.drop.html
[Build Your Own Shell using Rust]: https://www.joshmcguigan.com/blog/build-your-own-shell-rust/
[Stacked Borrows Implemented]: https://www.ralfj.de/blog/2018/11/16/stacked-borrows-implementation.html
[Middleware in Tide]: https://rust-lang-nursery.github.io/wg-net/2018/11/07/tide-middleware.html
[Running Rust natively in AWS Lambda and testing it locally]: https://medium.com/@bernardo.belchior1/running-rust-natively-in-aws-lambda-and-testing-it-locally-57080421426d
[Rust And Game Development]: https://alexene.github.io/2018/11/15/Rust-and-game-development.html
[Things Rust doesn’t let you do]: https://medium.com/@GolDDranks/things-rust-doesnt-let-you-do-draft-f596a3c740a5
[Generating Sudoku Boards pt. 3: Rust for WebAssembly]: https://medium.com/@rossharrison/generating-sudoku-boards-pt-3-rust-for-webassembly-85bd7294c34a
[proc_macro_attribute Revisited]: https://llogiq.github.io/2018/11/10/proc-macro.html
[flamer]: https://crates.io/crates/flamer
[overflower]: https://crates.io/crates/overflower
[Monadic do notation in Rust: Part I]: https://varkor.github.io/blog/2018/11/10/monadic-do-notation-in-rust-part-i.html

## Talks and Videos
