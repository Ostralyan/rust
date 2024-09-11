# Resources for ruste

## Books to get started
[The Rust Programming Language](https://doc.rust-lang.org/book/) - Welcome to The Rust Programming Language, an introductory book about Rust. The Rust programming language helps you write faster, more reliable software. High-level ergonomics and low-level control are often at odds in programming language design; Rust challenges that conflict. Through balancing powerful technical capacity and a great developer experience, Rust gives you the option to control low-level details (such as memory usage) without all the hassle traditionally associated with such control.

[Learning Rust With Entirely Too Many Linked Lists](https://rust-unofficial.github.io/too-many-lists/index.html#learn-rust-with-entirely-too-many-linked-lists) - In this series I will teach you basic and advanced Rust programming entirely by having you implement 6 linked lists.

[Comprehensive Rust](https://google.github.io/comprehensive-rust/index.html) - This is a free Rust course developed by the Android team at Google. The course covers the full spectrum of Rust, from basic syntax to advanced topics like generics and error handling.

[The Rust Performance Book](https://nnethercote.github.io/perf-book/title-page.html) - This book contains techniques that can improve the performance-related characteristics of Rust programs, such as runtime speed, memory usage, and binary size. The Compile Times section also contains techniques that will improve the compile times of Rust programs. Some techniques only require changing build configurations, but many require changing code.

[Rust Developer](https://robot-dreams-rust.mag.wiki/intro.html) - Over the next ten weeks, we will go through all the important of the concepts of the Rust programming language, both hands on and in practice via hands-on examples and homeworks.

[Rust Design Patterns](https://rust-unofficial.github.io/patterns/intro.html) - Rust is not object-oriented, and the combination of all its characteristics, such as functional elements, a strong type system, and the borrow checker, makes it unique. Because of this, Rust design patterns vary with respect to other traditional object-oriented programming languages. That’s why we decided to write this book. We hope you enjoy reading it! The book is divided in three main chapters:

[Effective Rust](https://effective-rust.com/title-page.html) - This book tries to help with these areas where programmers struggle, even if they already have experience with an existing compiled language like C++. As such—and in common with other Effective <Language> books—this book is intended to be the second book that a newcomer to Rust might need, after they have already encountered the basics elsewhere—for example, in The Rust Programming Language (Steve Klabnik and Carol Nichols, No Starch Press) or Programming Rust (Jim Blandy et al., O'Reilly).

[The Cargo Book](https://doc.rust-lang.org/nightly/cargo/index.html) - Cargo is the Rust package manager. Cargo downloads your Rust package’s dependencies, compiles your packages, makes distributable packages, and uploads them to crates.io, the Rust community’s package registry. You can contribute to this book on GitHub.

## Crates

### Http
[hyper](https://github.com/hyperium/hyper) - A protective and efficient HTTP library for all.

[tungstenite](https://github.com/snapview/tungstenite-rs) - Lightweight stream-based WebSocket implementation for Rust.

[tokio-tungstenite](https://github.com/snapview/tokio-tungstenite) - Asynchronous WebSockets for Tokio stack.

[reqwest](https://github.com/seanmonstar/reqwest) - An ergonomic, batteries-included HTTP Client for Rust.

[Surf](https://github.com/http-rs/surf) - Surf is a Rust HTTP client built for ease-of-use and multi-HTTP-backend flexibility. Whether it's a quick script, or a cross-platform SDK, Surf will make it work.

[prost](https://github.com/tokio-rs/prost) - prost is a Protocol Buffers implementation for the Rust Language. prost generates simple, idiomatic Rust code from proto2 and proto3 files.

[tonic](https://github.com/hyperium/tonic) - tonic is a gRPC over HTTP/2 implementation focused on high performance, interoperability, and flexibility. This library was created to have first class support of async/await and to act as a core building block for production systems written in Rust.

### Web Frameworks

[axum](https://github.com/tokio-rs/axum) - axum is a web application framework that focuses on ergonomics and modularity.

[actix-web](https://github.com/actix/actix-web) - Actix Web is a powerful, pragmatic, and extremely fast web framework for Rust

[Rocket](https://github.com/rwf2/Rocket) - Rocket is an async web framework for Rust with a focus on usability, security, extensibility, and speed.

[Tide](https://github.com/http-rs/tide) - Tide is a minimal and pragmatic Rust web application framework built for rapid development. It comes with a robust set of features that make building async web applications and APIs easier and more fun.

[Poem](https://github.com/poem-web/poem) - A full-featured and easy-to-use web framework with the Rust programming language.

[Warp](https://github.com/seanmonstar/warp) - A super-easy, composable, web server framework for warp speeds.

### WASM
[Yew](https://github.com/yewstack/yew) - Yew is a modern Rust framework for creating multi-threaded front-end web apps with WebAssembly.

### Database
#### Sql
[sqlx](https://github.com/launchbadge/sqlx) - sqlx is a library which provides a set of extensions on go's standard database/sql library. The sqlx versions of sql.DB, sql.TX, sql.Stmt, et al. all leave the underlying interfaces untouched, so that their interfaces are a superset on the standard ones. This makes it relatively painless to integrate existing codebases using database/sql with sqlx.

[diesel](https://github.com/diesel-rs/diesel) - Diesel gets rid of the boilerplate for database interaction and eliminates runtime errors without sacrificing performance. It takes full advantage of Rust's type system to create a low overhead query builder that "feels like Rust."

[diesel-async](https://github.com/weiznich/diesel_async) - Diesel-async provides an async implementation of diesels connection implementation and any method that may issue an query. It is designed as pure async drop-in replacement for the corresponding diesel methods. Similar to diesel the crate is designed in a way that allows third party crates to extend the existing infrastructure and even provide their own connection implementations.

[SeaORM](https://github.com/SeaQL/sea-orm) - SeaORM is a relational ORM to help you build web services in Rust with the familiarity of dynamic languages.

##### NoSql
[mongodb](https://github.com/mongodb/mongo-rust-driver)

[redis](https://github.com/redis-rs/redis-rs) - Redis-rs is a high level redis library for Rust. It provides convenient access to all Redis functionality through a very flexible but low-level API. It uses a customizable type conversion trait so that any operation can return results in just the type you are expecting. This makes for a very pleasant development experience.

[elasticsearch](https://github.com/elastic/elasticsearch-rs)

### Error Handling
[anyhow](https://github.com/dtolnay/anyhow) - This library provides anyhow::Error, a trait object based error type for easy idiomatic error handling in Rust applications.

[thiserror](https://github.com/dtolnay/thiserror) - This library provides a convenient derive macro for the standard library's std::error::Error trait.

### Serialization
[serde](https://github.com/serde-rs/serde) - Serde is a framework for serializing and deserializing Rust data structures efficiently and generically.

[serde_json](https://github.com/serde-rs/json) - Serde is a framework for serializing and deserializing Rust data structures efficiently and generically.

[bincode](https://github.com/bincode-org/bincode) - A compact encoder / decoder pair that uses a binary zero-fluff encoding scheme. The size of the encoded object will be the same or smaller than the size that the object takes up in memory in a running Rust program.

### Pub/Sub

[Lapin](https://github.com/amqp-rs/lapin) - This project follows the AMQP 0.9.1 specifications, targeting especially RabbitMQ.

[rust-rdkafka](https://github.com/fede1024/rust-rdkafka) - rust-rdkafka provides a safe Rust interface to librdkafka. This version is compatible with librdkafka v1.9.2+.

[google-cloud-rust](https://github.com/yoshidan/google-cloud-rust) - Rust packages for Google Cloud Platform services.

### Async & Concurrency
[tokio](https://github.com/tokio-rs/tokio) - A runtime for writing reliable, asynchronous, and slim applications with the Rust programming language.

[async-std](https://github.com/async-rs/async-std) - This crate provides an async version of std. It provides all the interfaces you are used to, but in an async version and ready for Rust's async/await syntax.

[futures](https://github.com/rust-lang/futures-rs) - futures-rs is a library providing the foundations for asynchronous programming in Rust. It includes key trait definitions like Stream, as well as utilities like join!, select!, and various futures combinator methods which enable expressive asynchronous control flow.

[mio](https://github.com/tokio-rs/mio) - Mio is a fast, low-level I/O library for Rust focusing on non-blocking APIs and event notification for building high performance I/O apps with as little overhead as possible over the OS abstractions.

[rayon](https://github.com/rayon-rs/rayon) - Rayon is a data-parallelism library for Rust. It is extremely lightweight and makes it easy to convert a sequential computation into a parallel one. It also guarantees data-race freedom.

[Crossbeam](https://github.com/crossbeam-rs/crossbeam) - This crate provides a set of tools for concurrent programming:

### Telemetry & Profiling

[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-rust) - OpenTelemetry is a collection of tools, APIs, and SDKs used to instrument, generate, collect, and export telemetry data (metrics, logs, and traces) for analysis in order to understand your software's performance and behavior. You can export and analyze them using Prometheus, Jaeger, and other observability tools.

[Prometheus](https://github.com/tikv/rust-prometheus) - This is the Rust client library for Prometheus. The main data structures and APIs are ported from Go client.

[sentry](https://github.com/getsentry/sentry-rust) - This workspace contains various crates that provide support for logging events and errors / panics to the Sentry error logging service.

### Cryptograph

[jsonwebtoken](https://github.com/Keats/jsonwebtoken)

[oauth2](https://github.com/ramosbugs/oauth2-rs) - An extensible, strongly-typed implementation of OAuth2

### Misc

[OnceCell](https://github.com/matklad/once_cell) - once_cell provides two new cell-like types, unsync::OnceCell and sync::OnceCell. OnceCell might store arbitrary non-Copy types, can be assigned to at most once and provide direct access to the stored contents. In a nutshell, API looks roughly like this

### Third Party Integrations

[async-stripe](https://github.com/arlyon/async-stripe)
