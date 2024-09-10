# Rust Aarhus meetup at the Alexandra Institute

Date: 2024-09-26

Rust Aarhus and [Alexandra Instituttet][ai] invites you to this free meetup for all interested in the programming language [Rust].

The program for the evening is:

- 18:05 - 18:10: Welcome (5 min)
- 18:15 - 19:00: SecGPT: using LLMs for secure Rust code (30+15 min)
- 19:00 - 19:10: A word from our sponsor (5-10 min)
- 19:10 - 20:10: Light dinner sponsored by Alexandra Instituttet
- 20:15 - 20:45: Hax - Rust for high-assurance cryptography (30 min)
- 20:50 - 21:00: Closing remarks (10 min)
- 21:00: Let's continue the discussion at a nearby bar

## SecGPT: using LLMs for secure Rust code

By [Benjamin Salling Hvass][bsh], [Mikkel Wienberg Madsen][mwm], [Gert Læssøe Mikkelsen][glm], [Bas Spitters][bs].

In the last couple of years, LLM based tools, like GitHub Copilot, have become a popular aide in software development.
They have been used for autocompletion, for translations and in reasoning. However, they have a tendency to hallucinate and to produce insecure code.
How well do they fare on rust, and can we use them to help us write safer and less vulnerable code?

Rust is a new and somewhat smaller language, which is less represented in the training data. So, one can expect some challenges.
At the same time, one can hope that rust's type checker and borrow checker can help to catch LLMs hallucinations.

In this talk we will go over several ways we have tried to use LLMs
in a more automated approach, from translation of other languages into rust, to fixing compiler errors and reasoning about software vulnerabilities.
The talk is also an invitation to collect feedback and experiences in the use of LLMs from the Rust Aarhus community.

[ The talk presents some of the outcomes of an explorative project supported by the CenSec cluster. ]


## Hax - Rust for high-assurance cryptography

By [Bas Spitters][bs]

Bas will present the Hax toolchain for high-assurance cryptography in Rust.
[Hax] uses Rust as a specification language for cryptographic primitives and protocols,
together with formal methods tools to link those specifications to highly optimized implementations.
Hax is being used in projects together with Microsoft research, Google, the Signal Foundation, ...
There is also interest from the IETF, which standardizes internet protocols.

Bas Spitters is associate professor CS, Aarhus University.


## Location
This meetup will be at INCUBA Katrinebjerg, Lille Auditorium, Åbogade 15, 8200 Aarhus. Please feel free to use the event chat on meetup to organize transportation if needed.

## Food
We will try to have a combination of vegan and non-vegan food. If you have special needs regarding food (e.g. allergies), please forward your request to tue@rustaarhus.dk.


[rust]: https://www.rust-lang.org/
[ai]: https://alexandra.dk/
[bsh]: https://www.linkedin.com/in/benjamin-salling-hvass-a2064a15a/
[mwm]: https://www.linkedin.com/in/mikkel-wienberg-madsen-9b3192170/
[glm]: https://www.linkedin.com/in/gertlm/
[bs]: https://www.linkedin.com/in/basspitters/
[hax]: https://github.com/hacspec/hax