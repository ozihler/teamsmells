# The Refactoring Master
## Explanation
Spends a lot of time refactoring code, even code that never changes.

## Why is it a problem?
* Refactoring code that never changes is a waste of money and resources.
* Every refactoring, as safe as it may be, introduces the risk of breaking something.

## How to fix it?
* Talk to the Refactoring Master about where to focus their refactoring efforts.
* Encourage the team to refactor code that is frequently changed continuously, and avoid dedicated refactoring stories. That way, the Refactoring Master may not feel the need to refactor code that never changes.

## Edge cases - when is it ok?
* Refactoring code before and during a change is a good practice.
* Refactoring code that was quickly added for e.g. an important release date is also a good practice.

## Questions and Indications to identify a Refactoring Master
* What is your favourite technical practice in software engineering? (Refactoring) 
* Do you think that refactoring is always a good thing? (Yes)

## How does it happen?
* Legacy Codebases that are hard to read and maintain may lead to an overcompensation, such that the Refactoring Master spends more time refactoring that required. 
* Lack of understanding for business value and the cost of refactoring.

## Related Smells
* [The Designer](The-Designer.md) is often also a Refactoring Master.