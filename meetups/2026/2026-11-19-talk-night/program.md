# Rust Aarhus meetup at EIVA

Date: 2026-11-19

Join us for an evening of talks, food, and networking at EIVA in Skanderborg. We have two exciting talks lined up, along with a light dinner sponsored by EIVA.

The program for the evening is:

- 18:05 - 18:10: Welcome (5 min)
- 18:15 - 18:55: Self-Healing Rust: Fast Feedback Loops for Coding Agents by Jordan Munch O'Hare (30 + 10 min)
- 18:55 - 19:40: Light dinner sponsored by EIVA
- 19:40 - 20:20: Company tour at EIVA (40 min)
- 20:25 - 20:50: Bevy under the hood by Ben Maguire (20 + 5 min)
- 20:50 - 21:00: Book Raffle and closing remarks (10 min)

## Self-Healing Rust: Fast Feedback Loops for Coding Agents

By Jordan Munch O'Hare

Rust gives coding agents excellent feedback, but running every check after every turn can get slow as a project grows.

I’ll show the self-healing loop I use in Rust projects: starting with fast checks, then running targeted Clippy and tests based on what changed. Cargo’s JSON output helps the agent understand failures and try again without involving me. The full test suite runs once the agent has settled, rather than after every turn.

The talk is about finding a practical balance: giving agents feedback quickly while still making sure “done” actually means the code has been checked.

Jordan Munch O'Hare is the founder of Self-Deprecated, an Aarhus-based company helping developers and organisations adopt agentic development. His background is in developer experience and platform engineering, with a particular interest in improving the systems through which software gets built.

He describes himself as a “nerd of nerds”, uses Rust among several languages, and is especially fond of Iced and its Elm-inspired architecture. His current focus is designing agent workflows around fast feedback, context management, attention management, and self-healing verification loops.

- [Jordan on LinkedIn](https://linkedin.com/in/jordanohare)

## Bevy under the hood

By Ben Maguire

Bevy is a game engine that is simple, data-driven and extensible. Every Bevy application lives under the law of the Entity Component System (ECS), which Bevy makes easy with an intuitive and ergonomic API. But at what cost?
Join me as I explore what's going on under the hood of the Bevy engine, how it implements ECS, and what compromises it made along the way.

Ben is a software developer originally from Australia. He's had experience building everything from web applications to control systems. He likes to tinker with Rust in his spare time, and daydream about ways to introduce it at work.

- [Ben on GitHub](https://github.com/BMaguire)

## Location

This meetup will be at EIVA, Niels Bohrs Vej 17, 8660 Skanderborg.

## Food

We will try to have a combination of vegan and non-vegan food. If you have special needs regarding food (e.g. allergies), please forward your request to tue@rustaarhus.dk.
