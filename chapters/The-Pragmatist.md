# The Pragmatist
## Explanation
A dev that removes abstractions that are necessary for the system to be maintainable by a team. 

## Why is it a problem?
* Code that solely relies on primitive types and structures is hard to read and maintain for other devs.
* The code does not reveal what it does in the domain, but only how it does it, hiding important business decisions.
* Over time, the code can become a [Big Ball of Mud](https://en.wikipedia.org/wiki/Big_ball_of_mud) where changes take a long time to implement or cannot be implemented at all.
* Code typically shows the [Primitive Obsession](https://refactoring.guru/smells/primitive-obsession) Code Smell.

## How to fix it?
* Introduce the Pragmatist to Domain-Driven Design
  * Deal with [a Nerd](The-Nerd.md) appropriately.

## Edge cases - when is it ok?

## Questions identify a Purist

## How does it happen?

## Related Smells
* [The Hacker](The-Hacker.md): closely related. A hacker wouldn't add unnecessary abstractions as it slows them down.
* Opposite of [The Designer](The-Designer.md).