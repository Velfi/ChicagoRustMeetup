# Building an Idiomatic C Wrapper in Rust

* Thread safety:
  * The docs say that the C API is **not** thread-safe.
  * Rust's definition of "thread-safe" is more robust than what the SpatialOS devs considered.
  * Various functions mutate state data in an unsynchronized way, but there's basically no global
    state to worry about.
  * Pretty much everything is actually `Send`, a lot of stuff is `Sync`, but schema types are not
    `Sync` due to internal mutation on fetches.
  * Initially defined schema pointer-types as unit structs, but that means they were both `Send`
    and `Sync` by default, which isn't correct!
* Schema pointer hacking.
* Enums are magic!
  * Other language SDKs use a pattern where you register a bunch of callbacks for each type of
    worker op, and then they internally dispatch to the correct callback. Rust enums basically do
    this automatically.
