# The Pragmatist
## Explanation
A dev that removes abstractions that are necessary for the system to be maintainable by a team. 

## Why is it a problem?
* Code that solely relies on primitive types and structures is hard to read and maintain for other devs.
* The code does not reveal what it does in the domain, but only how it does it, hiding important business decisions.
* Over time, the code can become a [Big Ball of Mud](https://en.wikipedia.org/wiki/Big_ball_of_mud) where changes take a long time to implement or cannot be implemented at all.
* Code typically shows the [Primitive Obsession](https://refactoring.guru/smells/primitive-obsession) Code Smell.

## How to fix it?
* Introduce the Pragmatist to Domain-Driven Design to show the value of abstractions for core subdomains.
  * Deal with [a Nerd](The-Nerd.md) appropriately.
* Find team members that are not agreeing with the Pragmatist, but are too shy to raise their voices (see [The Silent One](The-Silent-One.md)).
* Introduce Refactoring, Clean Code, and other high-level software engineering practices to the team.

## Edge cases - when is it ok?
* Simple CRUD applications may not need many abstractions. These often correspond to DDD supporting subdomains.
* Small scripts and one-off tools may not need abstractions, either.
* Procedural code is maintainable up to a couple of hundred lines. After that, it becomes hard to maintain, especially if the code evolves and many changing devs need to touch it.

## Questions identify a Purist
* What is your main focus when writing code? (e.g. "a small number of files")
* What do you think about Clean Code or Domain-Driven Design? (they typically think it's not pragmatic)
* What do you focus on when refactoring code? (e.g. only "remove duplications", not: "to make it more readable" or "to introduce domain concepts into the codebase")
* Also, listen to the language used. They will always say that "this is not pragmatic" or "this is not necessary".

## How does it happen?

## Related Smells
* [The Hacker](The-Hacker.md): closely related. A hacker wouldn't add unnecessary abstractions as they see no need for it.
* Opposite of [The Designer](The-Designer.md).
* Similar to [The Technologist](The-Technologist.md), but with a focus on low-level, procedural code design. This typically results in the use of mainly framework and low-level language features.
