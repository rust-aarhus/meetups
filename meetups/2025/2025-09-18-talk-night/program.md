# Rust Aarhus meetup at Mjølner Informatics

Date: 2025-09-18

Rust Aarhus invites you to this free meetup for all interested in the programming language [Rust].

The program for the evening is:

- 18:05 - 18:15: Welcome (10 min)
- 18:20 - 18:50: Securely running un-trusted code using WebAssembly and Rust by Mikkel Mørk Hegnhøj (20 + 10 min)
- 18:50 - 19:00: A word from our sponsor
- 19:00 - 20:00: Light dinner sponsored by Mjølner Informatics
- 20:00 - 20:35: Testing Tools and Tricks in Rust by Gustav Wengel (25 + 10 min)
- 20:40 - 20:50: Book Raffle (10 min)
- 20:50 - 21:00: Closing remarks (10 min)
- 21:00: Let's continue the discussion at a nearby bar

## Securely running un-trusted code using WebAssembly and Rust

By Mikkel Mørk Hegnhøj

In this talk, I'll walk you through a use-case we've been building with a customer. The customer wanted to provide developers the opportunity to write string processing code in Python to be applied to LLM prompts and answers (pre- and post-processing) meant to be integrated in user-facing applications. Using WebAssembly and the component model, we built an API using Rust, to safely execute un-trusted code in a WebAssembly sandbox.

Mikkel Mørk Hegnhøj is the head of product and engineering at Fermyon. He has a background in product management, customer success, and developer engagement. Beyond working on Fermyon's portfolio of services centered around WebAssembly and cloud, he has past experiences working at Microsoft on distributed systems platforms and cloud-native products, as well as developer tools. He’s passionate about developer and operator experiences, with a mission to make the path from idea to reality friction-less and quick. Mikkel lives in a tiny and beautiful village in Denmark.

- [Mikkel on GitHub](https://github.com/mikkelhegn/)
- [Mikkel on LinkedIn](https://www.linkedin.com/in/mikkelhegn/)

## Testing Tools and Tricks in Rust

By Gustav Wengel

This talk will cover some common tips and tricks for making testing in Rust faster, more idiomatic and more pleasant to do. It'll be a broad overview of some of the tools and tricks available in the Rust ecosystem for testing, focusing more on breadth, rather than depth.

I'm thinking we can cover in a roughly prioritized list, depending on the time we have available:

- Returning Results instead of calling .unwrap() inside tests
- Using "rstest" for test parameterization and fixture handling
- Using "insta" for snapshot testing
- Using "pretty_assertions" for more colorful diff views
- Writing expectation messages inside your "assert_eq" calls, instead of as comments.
- Running tests in serial mode if you need that with "serial_tests"
- Using "nextest" to speed up tests when you have multiple crates in a workspace

And things along that line!

Gustav Wengel has been working full-time with Rust for the last three years, building RESTful APIs at the german startup Climatiq.
Climatiq allows the users to embed CO2e and climate calculations into existing software.
He has previously worked extensively with C#, Python and Typescript, where he has been a core maintainer of popular open-source projects like [ts-jest](https://github.com/kulshekhar/ts-jest).

- [Gustav's page](https://www.gustavwengel.dk/)
- [Gustav on GitHub](https://github.com/GeeWee)
- [Gustav on LinkedIn](https://www.linkedin.com/in/gustav-wengel/)

## Location

This meetup will be at Mjølner Informatics, Finlandsgade 10, 8200 Århus, meeting room Valhalla. Please feel free to use the event chat on meetup to organize transportation if needed.

## Food

We will try to have a combination of vegan and non-vegan food. If you have special needs regarding food (e.g. allergies), please forward your request to tue@rustaarhus.dk.

[rust]: https://www.rust-lang.org/
