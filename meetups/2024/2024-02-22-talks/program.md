# Rust Aarhus meetup at Partisia

Date: 2024-02-22

Rust Aarhus invites you to this free meetup for all interested in the programming language [Rust].

The program for the evening is:

- 18:05 - 18:10: Welcome (5 min)
- 18:15 - 19:00: "Building serverless apps, using WASI, WebAssembly components using Rust" by Mikkel Mørk Hegnhøj (45 min incl Q&A)
- 19:05 - 19:15: Using Rust at Partisia by Partisia (10 min)
- 19:15 - 19:45: Light dinner sponsored by Partisia (30 min)
- 19:45 - 20:30: "Zero-copy deserialization in Rust" by Gustav Wengel (45 min incl Q&A)
- 20:35 - 20:45: Book Lottery (10 min)
- 20:45 - 20:55: A word from our sponsor (5-10 min)
- 20:55 - 21:00: Closing remarks (5 min)


## Building serverless apps, using WASI, WebAssembly components using Rust
By [Mikkel Mørk Hegnhøj][mmh]

An introduction to [WASI] (server-side WebAssembly), and the [WebAssembly component model][wasmcm], and how you can use [Spin] to easily get started. Spin is written in Rust, and has great support for writing server apps using Rust, as well as composing polyglot applications.

Mikkel, works at Fermyon, where he leads the product and developer relationships team. He has built cloud product for the last 10 years, most of the time at Microsoft. For the last year and a half, WebAssembly and Rust has been the thing he is mainly engaged in. Fermyon have created an open source project called Spin, a serverless framework, built in Rust, and using WebAssembly.


## Zero-copy deserialization in Rust
By [Gustav Wengel][gw]

When using Rust in many contexts, such as webservers or just parsing structured data from files, we need to deserialize text or bytes into Rust types. The de-facto library for this in the Rust ecosystem is [serde] - and we're going to explore how serde allows us to deserialize objects without actually allocating memory, by borrowing from the original source. We'll also dive into the [rkyv] crate as a zero-copy deserialization library if you really need every last bit of performance.

Gustav has been working with Rust for the past two years, building serverless RESTful API's at the startup Climatiq, that allows the users to embed CO2 and climate calculations into existing software. Before that he has worked in different startups with different tech stacks, and has been a core maintainer of popular open-source projects like [ts-jest].


## Location
This meetup will be at INCUBA Katrinebjerg, Lille Auditorium, Åbogade 15, 8200 Aarhus. Please feel free to use the event chat on meetup to organize transportation if needed.

## Food
We will try to have a combination of vegan and non-vegan food. If you have special needs regarding food (e.g. allergies), please forward your request directly to rustaarhus@gmail.com.


[rust]: https://www.rust-lang.org/
[wasi]: https://wasi.dev/
[wasmcm]: https://component-model.bytecodealliance.org/
[spin]: https://github.com/fermyon/spin
[mmh]: https://github.com/mikkelhegn
[gw]: https://github.com/GeeWee
[serde]: https://crates.io/crates/serde
[rkyv]: https://crates.io/crates/rkyv
[ts-jest]: https://github.com/kulshekhar/ts-jest