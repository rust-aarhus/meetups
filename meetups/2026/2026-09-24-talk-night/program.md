# Rust Aarhus meetup at SkyTEM

Date: 2026-09-24

Join us for an evening of talks, food, and networking at SkyTEM in Aarhus. We have two exciting talks lined up, along with a light dinner sponsored by SkyTEM.

The program for the evening is:

- 18:05 - 18:10: Welcome (5 min)
- 18:15 - 18:50: Beyond grep: structure-aware search for Rust code with srcsearch by Hamid Alavi Toussi (30 + 5 min)
- 18:50 - 19:00: A word from our sponsor
- 19:00 - 19:50: Light dinner sponsored by SkyTEM
- 19:50 - 20:10: A Rust journey by Andreas Corneliussen (15 + 5 min)
- 20:15 - 20:50: The Facets of Facet by Alexandra Østermark (30 + 5 min)
- 20:50 - 21:00: Book Raffle and closing remarks (10 min)

## Beyond grep: structure-aware search for Rust code with srcsearch

by Hamid Alavi Toussi

srcsearch is a lightweight search engine for source code and project documentation that I wrote in Rust. It parses Rust source files and Markdown documentation and indexes them using Tantivy, with BM25-based relevance ranking.

The key difference from grep-like tools is the unit being searched.

A line-oriented search tool matches individual lines. srcsearch instead indexes meaningful structures: Rust entities such as functions, structs, and implementations, as well as Markdown sections. Information belonging to an entity is kept together in fields such as its name, signature, documentation, and source code.

This means a query can match information distributed across an entire Rust entity. For example, one query term might occur in a type's declaration while another occurs in its documentation or methods. srcsearch can combine those signals and rank the entity as one result, even when no individual source line contains the complete query.

This is also useful for coding agents. An agent exploring an unfamiliar repository often does not know the exact identifier or string to search for. Instead, it may start with a higher-level task such as find the code responsible for filtering files or locate the documentation for the search configuration. Returning a small ranked set of relevant functions, types, implementations, and documentation sections can give the agent better starting points than a large list of matching lines. Because srcsearch runs locally and exposes structured results, it can also be used as a retrieval component inside agentic developer tools.

Hamid Alavi Toussi is a software engineer at Elsevier. He is interested in search and information retrieval, data management, and developer tooling, among other things.

- [Hamid on LinkedIn](https://www.linkedin.com/in/hamid-alavi-toussi-553751196/)
- [Hamid on GitHub](https://github.com/jslambda)
- [srcsearch on GitHub](https://github.com/jslambda/srcsearch)
- [srcsearch on Crates.io](https://crates.io/crates/srcsearch)

## A Rust journey

by Andreas Corneliussen

A talk about the journey we have had at SkyTEM. Starting at python build on embedded yocto, then python in containers on embedded yocto and now adding rust into the mix and liking it.

Andreas is Development Engineer at SkyTEM. Master of electronics. Experience in embedded programming using FPGAs, microcontrollers with bare-metal C, microcontrollers with RTOS and embedded linux. Now working in a team where we handle everything from timing critical FPGA programming over python and rust on embedded yocto linux to containers and databases in azure.

- [Andreas on LinkedIn](http://www.linkedin.com/in/andreascorneliussen)

## The Facets of Facet

by Alexandra Østermark

In the rust world we love our 0 cost abstractions, but what happens if we wanna pay just a few cents for a better abstraction, what superpowers can we get. In this talk we'll be discussing the serialization strategy of facet and serde, how they differ and what other superpowers we gain from paying a little bit of speed upfront

Facet is a general purpose reflection library which allows you to get the Shape of a struct, which on the surface seems like just an alternative (and slower) approach to serialization but doing it this way allows us to use the same derived data in ways extremely cool and helps us reduce boilerplate and ensuring correctness

Hi i'm Alexandra Østermark, i'm a software engineer at RE-ZIP.
Additionally i'm a contributor to facet, and i maintain thevenin, a circuit simulation library in rust

- [Alexandra on GitHub](https://github.com/cramt/)

## Location

This meetup will be at SkyTEM, Dyssen 2, 8200 Aarhus N.

## Food

We will try to have a combination of vegan and non-vegan food. If you have special needs regarding food (e.g. allergies), please forward your request to tue@rustaarhus.dk.
