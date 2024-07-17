# Rust Playground

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
- [rustdoc book](https://doc.rust-lang.org/rustdoc/what-is-rustdoc.html).

### Training

- [Rustlings](https://github.com/rust-lang/rustlings/) - an excellent learn-by-doing site, using small bounded exercises.
- [Rust by Example](https://doc.rust-lang.org/rust-by-example/) - a collection of runnable examples that illustrate various Rust concepts and standard libraries.
- [Rust Cookbook](https://rust-lang-nursery.github.io/rust-cookbook/)
- [Rust in Motion](https://www.manning.com/livevideo/rust-in-motion?a_aid=cnichols&a_bid=6a993c2e) - video course, paid.
- [Tour of Rust](https://tourofrust.com/)
- [Rust Development Classes](https://rust-classes.com/)
- From C to Rust: [part 1](https://levelup.gitconnected.com/from-c-to-rust-f280f160e05d), [part 2](https://levelup.gitconnected.com/from-c-to-rust-part-ii-aaaab74941a0), [part 3](https://levelup.gitconnected.com/from-c-to-rust-part-iii-44c9dce4f5d3), [part 4](https://levelup.gitconnected.com/from-c-to-rust-part-4-embracing-flexibility-1266d8d95323).
- [100 Exercises to Learn Rust](https://rust-exercises.com/).
- [Code Crafters Master Rust Exercises](https://app.codecrafters.io/tracks/rust).
- [Tech-rs](https://github.com/trifectatechfoundation/teach-rs) is a university-level Rust course for CS students, available to anyone.
- [Rust-101](https://www.ralfj.de/projects/rust-101/main.html), an online tutorial.
- [rust-learning](https://github.com/ctjhoa/rust-learning) is a curated collection of blog posts, videos, etc., on learning Rust.

### Books

- [The Rust Book](https://doc.rust-lang.org/book/) - the definitive documentation.
- [Command-line apps in Rust book](https://rust-cli.github.io/book/index.html)
- [Rust and WASM book](https://rustwasm.github.io/docs/book/)
- [Embedded Rust book](https://doc.rust-lang.org/stable/embedded-book/)
- [Programming in Rust](https://www.oreilly.com/library/view/programming-rust-2nd/9781492052586/)
- [Rust in Action](https://www.manning.com/books/rust-in-action) - book, paid.
- [Zero to Production in Rust](https://www.zero2prod.com/index.html).
- [Rustdoc book](https://doc.rust-lang.org/rustdoc/index.html)
- [Rustc manual](https://doc.rust-lang.org/rustc/index.html)

### Ecosystem

- [Cargo book](https://doc.rust-lang.org/cargo/index.html)
- [crates.io](https://crates.io/) - the official Rust package repository.
- [Blessed](https://blessed.rs/crates) - an unofficial guide to choosing crates, manually updated.
- [lib.rs](https://lib.rs/) - an automated Rust crate catalog.
- [docs.rs](https://docs.rs/) - crate documentation.
- [Awesome Rust](https://github.com/rust-unofficial/awesome-rust)
- [cargo-license](https://github.com/onur/cargo-license) is a useful tool that prints out the licenses of all dependencies in your package.
- [cargo-audit](https://docs.rs/cargo-audit/latest/cargo_audit/) is a tool that scans all the dependencies and versions in your package for any known vulnerabilities.

## Useful Articles

### General

- [Compiler error index](https://doc.rust-lang.org/error_codes/error-index.html)
- [Design Patterns in Rust](https://rust-unofficial.github.io/patterns/) - [PDF](https://rust-unofficial.github.io/patterns/rust-design-patterns.pdf)
- When you're building, you sometimes need to know about [environment variables](https://doc.rust-lang.org/cargo/reference/environment-variables.html#environment-variables-cargo-sets-for-build-scripts) used by the Rust build process. Note especially `CARGO_MANIFEST_DIR` which you can use to find the root of your source code from a target build directory. Also note that the builds run by `publish` run in the context of a target directory, so you may be unpleasantly surprised by a `build` that works, but a `publish` that fails.
- [Command Line Applications in Rust](https://rust-cli.github.io/book/).
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
- [Borrow checking, RC, GC, and the Eleven Other Memory Safety Approaches](https://verdagon.dev/grimoire/grimoire).
- [The search for easier safe systems programming](https://www.sophiajt.com/search-for-easier-safe-systems-programming/) - this article describes a new language called [June](https://github.com/sophiajt/june), Rust-like, but with simpler semantics.
- [The ultimate guide to Rust newtypes](https://www.howtocodeit.com/articles/ultimate-guide-rust-newtypes).
- [Rust ownership explained: merging linked lists](https://www.howtocodeit.com/articles/rust-ownership-explained-linked-lists).
- [Rust Options in Practice](https://willbaker.dev/posts/result-and-option/) - useful article on the details of Rust `Option`.
- [Changes to `u128`/`i128` layout in 1.77 and 1.78](https://blog.rust-lang.org/2024/03/30/i128-layout-update.html).
- [Long-term Rust Project Maintenance](https://corrode.dev/blog/long-term-rust-maintenance/) - a **really good** article on Rust maintenance, covering lots of topis (e.g., how do you choose which 3rd-party crates to use).

## Error Handling

- [Rust error handling cheat-sheet](https://gist.github.com/e-t-u/70f25d4566468adc43a4df43667cedb6).
- [The Definitive Guide to Rust Error Handling](https://www.howtocodeit.com/articles/the-definitive-guide-to-rust-error-handling).

## Containers

- [First steps with Docker + Rust](https://dev.to/rogertorres/first-steps-with-docker-rust-30oi) - a useful article on getting a Rust multi-stage build working, this can give you an image size of about 100MB.
- https://dev.to/mattdark/rust-docker-image-optimization-with-multi-stage-builds-4b6c - a newer article, which mentions distroless, haven't tried this, but it might be a better option than Alpine/MUSL.
- [Creating Lightweight Docker Images with Rust](https://medium.com/@pabloperezaradros/creating-lightweight-docker-images-with-rust-0db47cb014a9) - this article uses Alpine.

### Test

- Article on [Rust code coverage](https://blog.rng0.io/how-to-do-code-coverage-in-rust/) from 2022.
- The [test chapter](https://doc.rust-lang.org/book/ch11-00-testing.html) from the Rust book.
- [How to organize your Rust tests](https://blog.logrocket.com/how-to-organize-rust-tests/).
- [Reaching 100% code coverage in Rust](https://trane-project.github.io/blog/100_code_coverage.html).
- [Code coverage in Rust](https://rrmprogramming.com/article/code-coverage-in-rust/).
- `cargo-llvm-cov` is a wrapper around the gory details described here: https://doc.rust-lang.org/rustc/instrument-coverage.html.
- [Mocking in Rust: Mockall and alternatives](https://blog.logrocket.com/mocking-rust-mockall-alternatives/).
- [Mocking in Async Rust](https://www.vortexa.com/insights/technology/mocking-in-async-rust/).
- [Rust fuzz book](https://rust-fuzz.github.io/book/cargo-fuzz.html).
- [Properly Testing Concurrent Data Structures](https://matklad.github.io/2024/07/05/properly-testing-concurrent-data-structures.html).
- [The sad state of property-based testing libraries](https://stevana.github.io/the_sad_state_of_property-based_testing_libraries.html).

### Networking

- [TCP servers in Rust](https://app.codecrafters.io/concepts/rust-tcp-server). This discusses the basics of TCP servers in Rust, using synchronous APIs from the standard library.
- Tokio [tutorial](https://tokio.rs/tokio/tutorial).
- The [Remote development with Rust on fly.io](https://fasterthanli.me/articles/remote-development-with-rust-on-fly-io) article by `fasterthanli.me` has a [good section in the middle](https://fasterthanli.me/articles/remote-development-with-rust-on-fly-io#a-naive-tcp-proxy-with-tokio) on building a TCP proxy.
- [A TCP proxy in 30 lines of Rust](https://github.com/0xekez/tcp-proxy).
- Another Rust [TCP proxy](https://github.com/hishboy/rust-tcp-proxy) example.
- [What I learned from making a DNS client in Rust](https://blog.adamchalmers.com/making-a-dns-client/).

### HTTP

- [Mediocre Engineer’s guide to HTTPS](https://devonperoutky.super.site/blog-posts/mediocre-engineers-guide-to-https) - this one isn't Rust-related.
- Article on Rust HTTP clients: https://blog.logrocket.com/best-rust-http-client/.
- [The HTTP crash course nobody asked for](https://fasterthanli.me/articles/the-http-crash-course-nobody-asked-for) - discusses `reqwest`, `hyper`, HTTP/2.

### Pingora

- [Pingora](https://github.com/cloudflare/pingora) is a Rust framework from Cloudflare for building proxies (and more) (2022-2024).
- Pingora [blog post](https://blog.cloudflare.com/how-we-built-pingora-the-proxy-that-connects-cloudflare-to-the-internet).
- Pingora is [open-source](https://blog.cloudflare.com/pingora-open-source).
- [River](https://www.memorysafety.org/initiative/reverse-proxy/) is a reverse proxy based on Pingora, being built by ISRG, Cloudflare, Shopify, Chainguard.
- A simple [reverse proxy](https://github.com/randommm/pingora-reverse-proxy) built on Pingora.
- [Oxy](https://blog.cloudflare.com/introducing-oxy/), another Rust-based proxy framework from Cloudflare (2023). This one is proprietary, and only some components have been open-sourced ([boring](https://github.com/cloudflare/boring), [quiche](https://github.com/cloudflare/quiche)).

### gRPC

- [Tonic](https://github.com/hyperium/tonic) is probably the most comprehensive Rust implementation of gRPC. See also it's [crate page](https://docs.rs/tonic/latest/tonic/).
- Tonic has been [adopted](https://groups.google.com/g/grpc-io/c/ExbWWLaGHjI) by the CNCF gRPC team as the basis for a future standard full-featured Rust gRPC implementation.
- [Tonic examples](https://github.com/hyperium/tonic/tree/master/examples).
- [Tonic build](https://docs.rs/tonic-build/latest/tonic_build/).
- [grpc](https://crates.io/crates/grpc) is another Rust gRPC implementation.
- [Rust and gRPC: A complete guide](https://blog.logrocket.com/rust-and-grpc-a-complete-guide/).
- [Introduction to gRPC in Rust](https://romankudryashov.com/blog/2021/04/grpc-rust/).
- [Building gRPC APIs with Rust](https://konghq.com/blog/engineering/building-grpc-apis-with-rust).
- [gRPC over HTTP/2 in Rust](https://www.linkedin.com/pulse/grpc-over-http2-rust-luis-soares-m-sc-/).
- [Quick Start to gRPC Using Rust](https://golangly.com/index.php/2023/10/06/quick-start-to-grpc-using-rust/).
- [grpccurl](https://github.com/fullstorydev/grpcurl), a command-line gRPC client.

### Async

- [The Async Rust Book](https://rust-lang.github.io/async-book/).
- [Async Rust Is A Bad Language](https://bitbashing.io/async-rust.html).
- [A practical guide to async in Rust](https://blog.logrocket.com/a-practical-guide-to-async-in-rust/).
- [An Introduction to Asynchronous Programming in Rust and a High-level Overview of Tokio's Architecture](https://moslehian.com/posts/2023/1-intro-async-rust-tokio/).
- [Async Programming in Rust — Exploring Tokio and Async-std](https://medium.com/@AlexanderObregon/async-programming-in-rust-exploring-tokio-and-async-std-97d4b524cef0).
- [The State of Async Rust: Runtimes](https://corrode.dev/blog/async/) - excellent state of async Rust, as of February 2024.

### JSON

- [Parsing JSON with Rust](https://whoisryosuke.com/blog/2022/parsing-json-with-rust).
- [Serde](https://serde.rs/) is a framework for serializing and deserializing Rust data structures efficiently and generically.
- [Serde JSON](https://github.com/serde-rs/json).
- [serde_valid](https://docs.rs/serde_valid/latest/serde_valid/), adds schema validation to `serde`.
- [jsonschema-rs](https://github.com/serde-rs/json), a JSON schema validator.

### Caching

- [Caches in Rust](https://matklad.github.io/2022/06/11/caches-in-rust.html).
- [cached](https://github.com/jaemk/cached) provides implementations of several caching structures as well as a handy macros for defining memoized functions.
- [lru](https://lib.rs/crates/lru), an LRU cache implementation.
- [cacache](https://lib.rs/crates/cacache), a content-addressable, key-value, high-performance, on-disk cache.
- [Building a Rust Caching System: A Step-by-Step Guide](https://medium.com/@emmaxcharles123/building-a-rust-caching-system-a-step-by-step-guide-8eda3912455d).

### Parsing

- [A Beginners Guide to Parsing in Rust](https://depth-first.com/articles/2021/12/16/a-beginners-guide-to-parsing-in-rust/)
- [Parsing with nom, a gentle introduction](https://stevedonovan.github.io/rust-gentle-intro/nom-intro.html)
- [Text Processing in Rust](https://www.linuxjournal.com/content/text-processing-rust)
- [Beginner, Intermediate and Advanced Parsing in Rust](https://www.rustadventure.dev/beginner-intermediate-and-advanced-parsing-in-rust)
- [Parsing Text with nom](https://blog.adamchalmers.com/nom-chars/)
- [Learning Parser Combinators With Rust](https://bodil.lol/parser-combinators/).
- [Parsing in Rust with nom](https://blog.logrocket.com/parsing-in-rust-with-nom).

### Macros

- **NOTE** There is an [RFC](https://github.com/rust-lang/rfcs/blob/master/text/1584-macros.md) in [progress](https://github.com/rust-lang/rust/issues/39412) for a 2.0 version of macros.
- [Macros chapter in the Rust Book](https://doc.rust-lang.org/book/ch19-06-macros.html).
- [The Little Book of Rust Macros](https://veykril.github.io/tlborm/) - this is a very good in-depth explanation with examples.
- [Macros section in Rust By Example](https://doc.rust-lang.org/rust-by-example/macros.html).
- [Macros chapter in the Language Reference](https://doc.rust-lang.org/reference/macros.html).
- [Procedural Macros in Rust – A Handbook for Beginners](https://www.freecodecamp.org/news/procedural-macros-in-rust/).
- [Macros in Rust: A tutorial with examples](https://blog.logrocket.com/macros-in-rust-a-tutorial-with-examples/).
- [Writing production Rust macros with macro_rules!](https://www.howtocodeit.com/articles/writing-production-rust-macros-with-macro-rules).

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
- [anyhow](https://docs.rs/anyhow/latest/anyhow/index.html) - idiomatic error handling.

### Low-level

- [packed-struct](https://crates.io/crates/packed-struct) - this is a library for binary packing/unpacking to/from Rust structs; it is very powerful, but somewhat tricky to get the hang of initially. Documentation is sparse, and you will encounter some bizarre compiler errors when things go wrong. However, it has proven to be extremely useful. You probably need to enable the `"byte_types_256"` and `"byte_types_64"` features. I discovered by trial and error that `u128`s are not supported, i.e. `u64` is the biggest data type it will accept.
- [prost](https://crates.io/crates/prost) - Protobuf implementation.
- [prost-types](https://crates.io/crates/prost-types) - Prost definitions for Protobuf well-known types; I don't know if this is actually n3eded, but `prost` pulled it in.
- [prost-build](https://crates.io/crates/prost-build) - this is a build tool that wraps `protoc`. It really is super-easy to use. Very nice.
- [nom](https://docs.rs/nom/latest/nom/) - a parser combinator library written in Rust.
- [bitvec](https://docs.rs/crate/bitvec/latest) - bit manipulation library.

### Test

- [ctor](https://docs.rs/ctor/latest/ctor/) - this is a macro that can define global (per executable) constructor/destructor functions. I have used it to register a test setup function per module, to ensure that logging is only initialized once.
- [cargo-llvm-cov](https://lib.rs/crates/cargo-llvm-cov) - a very handy Cargo tool to run instrumented tests and generate coverage analysis.
- [mockall](https://docs.rs/mockall/).
- [serial_test](https://docs.rs/serial_test/0.4.0/serial_test/) - a useful crate to add a `serial` attribute to serialise Rust tests (which are all parallel by default).
- [socket-server-mocker](https://docs.rs/socket-server-mocker/latest/socket_server_mocker/) is a useful crate that allows you to mock arbitrary socket operations, handy when you're dealing with TCP protocols.
- [mockito](https://docs.rs/mockito/latest/mockito/) is a more comprehensive HTTP mocking library.
- [httpmock](https://docs.rs/httpmock/latest/httpmock/) is another HTTP mocking library.
- [wiremock](https://docs.rs/wiremock/latest/wiremock/) is another HTTP mocking library, which seems to be the newest of this set.
- [proptest](https://github.com/proptest-rs/proptest) is a property-based testing framework.
- [quickcheck](https://github.com/BurntSushi/quickcheck) is another property-testing framework, based on the Haskell original.
- [loom](https://github.com/tokio-rs/loom) is a test library for testing concurrent Rust code.

### HTTP

- Rust curl package: https://docs.rs/curl/0.4.46/curl/index.html.
- Hyper package: https://hyper.rs/ and https://github.com/hyperium/hyper.
- Hyper stubs: https://docs.rs/hyper-stub/latest/hyper_stub/ (useful for unit tests).

### gRPC

- [tonic](https://docs.rs/tonic/latest/tonic/).
- [tonic_build](https://docs.rs/tonic-build/latest/tonic_build/).

### Async

- Tokio: https://tokio.rs/ - the de-facto async runtime for Rust.

### JSON

- [serde](https://docs.rs/serde/latest/serde/).
- [serde_json](https://crates.io/crates/serde_json).
- [jsonschema](https://crates.io/crates/jsonschema).

### DNS

- [rustdns](https://docs.rs/rustdns/latest/rustdns/).
- [hickory-dns](https://github.com/hickory-dns/hickory-dns).
- [domain](https://crates.io/crates/domain).
- [trust-dns](https://trust-dns.org/).
