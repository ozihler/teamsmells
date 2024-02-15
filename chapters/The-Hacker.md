# The Hacker
## Explanation
Adds code quickly and without regard for the underlying design.

## Why is it a problem?
* every hack that disregards the design makes the codebase harder to maintain.
* hacks accumulate quickly, the cost of understanding them increases exponentially.
* most of the time, not even the hacker understands the code they wrote after a couple of days or weeks.

## How to fix it?
* avoid hacks as much as possible.
* if a hack is necessary, document it and make sure it is reviewed by at least one other team member.
* if it's a notorious hacker, understand why they are hacking and address the underlying problem.

## Edge cases - when is it ok?
* sometimes, a hack is inevitable. But, it should be a tool like any other. The key is to mark and document it clearly and to make everyone aware of that hack to avoid accidental "fixing" or refactoring.

## Questions and Indications to identify a Hacker
* What's your main goal when developing software? (e.g. speed, quality, maintainability, etc.)
* Was there a specific reason why you disregarded the normal design?

## How does it happen?
* No design
* No pair programming or code reviews
* No team