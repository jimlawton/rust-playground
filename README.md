# rust-playground

## Rust Resources

### Fundamentals

- [Rust language site](https://www.rust-lang.org/) - the definitive source.
- [The Rust Book](https://doc.rust-lang.org/book/) - the definitive documentation, read this.
  - You can get a local copy of the book by doing: `cargo install thebook` which installs the `thebook` command.
- [Comprehensive Rust](https://google.github.io/comprehensive-rust/) - Rust course by the Android team at Google.
- [Effective Rust](https://effective-rust.com/)
- [The Mediocre Programmers Guide to Rust](https://www.hezmatt.org/~mpalmer/blog/2024/05/01/the-mediocre-programmers-guide-to-rust.html) - despite the title, this is a very useful article!.

### Language Resources

- [Standard Library](https://doc.rust-lang.org/std/index.html)
- [Rust editions](https://doc.rust-lang.org/edition-guide/index.html)
- [Rust Language Reference](https://doc.rust-lang.org/reference/index.html)
- [The Rustonomicon](https://doc.rust-lang.org/nomicon/index.html) - unsafe Rust
- [Idiomatic Rust](https://github.com/mre/idiomatic-rust)
- [Rust Language Cheat Sheet](https://cheats.rs/) - [PDF](https://cheats.rs/dl/rust_cheat_sheet_a4.pdf)

### Training

- [Rustlings](https://github.com/rust-lang/rustlings/) - an excellent learn-by-doing site, using small bounded exercises.
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - a collection of runnable examples that illustrate various Rust concepts and standard libraries.
- [Command-line apps in Rust book](https://rust-cli.github.io/book/index.html)
- [Rust and WASM book](https://rustwasm.github.io/docs/book/)
- [Embedded Rust book](https://doc.rust-lang.org/stable/embedded-book/)
- [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)
- [Rust in Action](https://www.manning.com/books/rust-in-action) - book, paid.
- [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - video course, paid.
- [Tour of Rust](https://tourofrust.com/)
- [Rust Development Classes](https://rust-classes.com/)

### Ecosystem

- [Cargo book](https://doc.rust-lang.org/cargo/index.html)
- [Rustdoc book](https://doc.rust-lang.org/rustdoc/index.html)
- [Rustc manual](https://doc.rust-lang.org/rustc/index.html)
- [Compiler error index](https://doc.rust-lang.org/error_codes/error-index.html)
- [Design Patterns in Rust](https://rust-unofficial.github.io/patterns/) - [PDF](https://rust-unofficial.github.io/patterns/rust-design-patterns.pdf)
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)

## Useful Articles

### General

- [Learn how to read a file in Rust](https://blog.logrocket.com/how-to-read-files-rust/).
- [Understanding String and &str in Rust](https://blog.logrocket.com/understanding-rust-string-str/).
- [Understanding the Rust borrow checker](https://blog.logrocket.com/introducing-rust-borrow-checker/).
- [5 automatic verification tools for Rust and when to use each](https://blog.logrocket.com/5-automatic-verification-tools-rust/).
- [Optimizing CI/CD pipelines in your Rust projects](https://blog.logrocket.com/optimizing-ci-cd-pipelines-rust-projects/).
- [A guide to cross-compilation in Rust](https://blog.logrocket.com/guide-cross-compilation-rust/).
- [Optimizing Rust code with LLVM: A detailed breakdown](https://blog.logrocket.com/optimizing-rust-code-llvm/).
- [Understanding Rust disambiguating traits: Copy, Clone, and Dynamic](https://blog.logrocket.com/disambiguating-rust-traits-copy-clone-dynamic/).
- [How to deploy Lambda functions in Rust](https://blog.logrocket.com/deploy-lambda-functions-rust/).
- [24 days of Rust blog](https://zsiciarz.github.io/24daysofrust/index.html).

### Test

- Article on [Rust code coverage](https://blog.rng0.io/how-to-do-code-coverage-in-rust/) from 2022.
- The [test chapter](https://doc.rust-lang.org/book/ch11-00-testing.html) from the Rust book.
- [How to organize your Rust tests](https://blog.logrocket.com/how-to-organize-rust-tests/).
- [Reaching 100% code coverage in Rust](https://trane-project.github.io/blog/100_code_coverage.html).
- [Code coverage in Rust](https://rrmprogramming.com/article/code-coverage-in-rust/).
- `cargo-llvm-cov` is a wrapper around the gory details described here: https://doc.rust-lang.org/rustc/instrument-coverage.html.
- [Mocking in Rust: Mockall and alternatives](https://blog.logrocket.com/mocking-rust-mockall-alternatives/).
- [Mocking in Async Rust](https://www.vortexa.com/insights/technology/mocking-in-async-rust/).

### HTTP

- Article on Rust HTTP clients: https://blog.logrocket.com/best-rust-http-client/.
- [The HTTP crash course nobody asked for](https://fasterthanli.me/articles/the-http-crash-course-nobody-asked-for) - discusses `reqwest`, `hyper`, HTTP/2.

### Async

- [The Async Rust Book](https://rust-lang.github.io/async-book/).
- [Async Rust Is A Bad Language](https://bitbashing.io/async-rust.html).
- [A practical guide to async in Rust](https://blog.logrocket.com/a-practical-guide-to-async-in-rust/).

## Useful Crates

These are crates I have found useful.

### Logging

- [log](https://crates.io/crates/log) - a lightweight logging facade, common API for all logging implementations.
- [env_logger](https://docs.rs/env_logger/latest/env_logger/) - a logger that can be configured using env variables.
- [pretty_env_logger](https://crates.io/crates/pretty_env_logger) - a pretty logger implementation, which does colorizing, based on env_logger. This produces nice output, as long as you don't want to customize it. I switched to `env_logger`, once I started to do anything fancy.
- [test-log](https://crates.io/crates/test-log) - a replacement for `#[test]` that initialises logging in test runs.

### CLI

- [clap](https://crates.io/crates/clap) - pretty much the standard Rust CLI arg parser; very simple to use, ensure you enable the `"derive"` feature.

### General

- [hex-literal](https://crates.io/crates/hex-literal) - a handy `hex!` macro for converting hex literals to static byte arrays at compile time.
- [phf](https://crates.io/crates/phf) - perfect hash function data structures; very useful for building static maps. Enable the `"macros"` feature.
- [rand](https://crates.io/crates/rand) - RNG library; this is very comprehensive, see [Rust Rand Book](https://rust-random.github.io/book).
- [sha2](https://crates.io/crates/sha2) - a pure Rust implementation of SHA family (including SHA-256, SHA-512).
- [snafu](https://crates.io/crates/snafu) - a nice way of constructing error enum types.
- [uuid](https://crates.io/crates/uuid) - UUID library, can convert to/from a `u128`. You probably want to enable the `"v4"` feature.
- AWS SDK for Rust: https://github.com/awslabs/aws-sdk-rust,https://aws.amazon.com/sdk-for-rust/.

### Low-level

- [packed-struct](https://crates.io/crates/packed-struct) - this is a library for binary packing/unpacking to/from Rust structs; it is very powerful, but somewhat tricky to get the hang of initially. Documentation is sparse, and you will encounter some bizarre compiler errors when things go wrong. However, it has proven to be extremely useful. You probably need to enable the `"byte_types_256"` and `"byte_types_64"` features. I discovered by trial and error that `u128`s are not supported, i.e. `u64` is the biggest data type it will accept.
- [prost](https://crates.io/crates/prost) - Protobuf implementation.
- [prost-types](https://crates.io/crates/prost-types) - Prost definitions for Protobuf well-known types; I don't know if this is actually n3eded, but `prost` pulled it in.
- [prost-build](https://crates.io/crates/prost-build) - this is a build tool that wraps `protoc`. It really is super-easy to use. Very nice.

### Test

- [ctor](https://docs.rs/ctor/latest/ctor/) - this is a macro that can define global (per executable) constructor/destructor functions. I have used it to register a test setup function per module, to ensure that logging is only initialized once.
- [cargo-llvm-cov](https://lib.rs/crates/cargo-llvm-cov) - a very handy Cargo tool to run instrumented tests and generate coverage analysis.
- [mockall](https://docs.rs/mockall/).
- [serial_test](https://docs.rs/serial_test/0.4.0/serial_test/) - a useful crate to add a `serial` attribute to serialise Rust tests (which are all parallel by default).


### HTTP

- Rust curl package: https://docs.rs/curl/0.4.46/curl/index.html.
- Hyper package: https://hyper.rs/ and https://github.com/hyperium/hyper.
- Hyper stubs: https://docs.rs/hyper-stub/latest/hyper_stub/ (useful for unit tests).

### Async

- Tokio: https://tokio.rs/ - the de-facto async runtime for Rust.
