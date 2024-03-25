# Rust Aarhus meetup at MFT Energy

Date: 2024-04-25

Rust Aarhus invites you to this free meetup for all interested in the programming language [Rust].

The program for the evening is:

- 18:05 - 18:15: Welcome (10 min)
- 18:15 - 18:50: Home Automation with Rust by Cosmin Constantin Lazar (30 min + 5 min Q&A)
- 18:50 - 19:00: A word from our sponsor, [MFT Energy][mft] (5-10 min)
- 19:00 - 19:45: Light dinner sponsored by [MFT Energy][mft] (45 min)
- 19:45 - 20:05: Open slot for one or two talks (20 min)
- 20:10 - 20:50: Building Rust for Production by Kasper Juul Hermansen (30 min + 10 min Q&A)
- 20:55 - 21:00: Closing remarks (5 min)
- 21:00: Let's continue the discussion at a nearby bar


## Home Automation with Rust
By [Cosmin Constantin Lazar][ccl]

In this beginner-level talk, Cosmin will share his journey learning Rust through a hands-on project: building an integration for [Home Assistant](https://github.com/home-assistant). This integration scrapes the [Kredsløb](https://www.kredslob.dk/produkter-og-services/genbrug-og-affald/affaldsbeholdere/toemmekalender) website to fetch garbage collection schedules for a specified address and then integrates these schedules into [Home Assistant](https://github.com/home-assistant). The talk will delve into the [source code](https://github.com/CosminLazar/ha-mitaffald) of the project, discuss the Rust crates utilized, and explore the software development lifecycle (SDLC) processes followed to bring this integration to life. This session is designed to offer practical insights into Rust development, making it a perfect opportunity for beginners eager to see how Rust projects are developed from concept to completion.

For the past 16 years, Cosmin has been building professional software solutions using the Microsoft .NET stack, tackling various industries like automotive, healthcare, classifieds, and commodity trading. He has served in roles ranging from a core contributor to leading teams, with positions including software developer, solution architect, and cloud solution architect. As a father of two, his limited free time is now spent on small home automation projects.


## Building Rust for Production
By [Kasper Juul Hermansen][kjh]

Building Rust with Cargo is quite easy - until it is isn't. In this talk I will go into how to build
Rust for production so that you get the most out of Cargo, solve common pitfalls, and get a fast 
and effective development environment. As a bonus I am gonna give a sneak peek of how to build Rust
effectively for a [Docker] container using [Dagger].

Kasper is a Developer Experience Engineer working at Lunar where he currently spends his time working 
on developer tooling, and building high performance data application, mostly in [golang]. 
In his spare time he maintains the [dagger rust sdk], and moonlights as a Rust developer


## Rust, Flutter and AI for Nature Conservation
By [José Díaz][jid]

[Are we GUI yet?](https://areweguiyet.com/) the answer is yes. Rust powers incredibly efficient and speedy software, meanwhile Flutter makes crafting stunning UIs a breeze. What's even better? Combining the two is a piece of cake! Join me as I dive into how this seamless fusion not only makes development a joy but also unlocks some seriously practical AI inference workflows.

José is an Engineer with a passion for AI research in environmental applications.  With experience in Full Stack and Machine Learning Engineering, he focuses on building new tools that can help protect biodiversity and nature across Chile and the world.

## Location
This meetup will be at Margrethepladsen 4, 3, 8000 Aarhus (bottom floor of Scandinavian Center).


## Food
We will try to have a combination of vegan and non-vegan food. If you have special needs regarding food (e.g. allergies), please forward your request to tue@rustaarhus.dk.


[rust]: https://www.rust-lang.org/
[mft]: https://mft-energy.com/
[ccl]: https://www.linkedin.com/in/cosminconstantinlazar/
[kjh]: https://github.com/kjuulh
[dagger]: https://dagger.io/
[dagger rust sdk]: https://github.com/dagger/dagger/tree/main/sdk/rust
[docker]: https://www.docker.com/
[golang]: https://go.dev/
