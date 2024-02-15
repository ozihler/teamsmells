# The Designer
## Explanation
Introduces superfluous abstractions early into a rapidly changing system, slowing down development in the process
Abstractions are classes, methods, functions, or other constructs that hide the underlying complexity of a system. 
They are a powerful tool to manage complexity, but they can also be overused.

## Why is it a problem?
* If systems change frequently, too many abstraction layers may slow down development as they first need to be inlined.
* With every additional abstraction, the chance for introducing a wrong abstraction or mixing abstraction levels increases as well.

## How to fix it?
* Indicate to the designer how the abstractions are hard to maintain.
* Encourage the "Rule of 3", meaning to only refactor code that was duplicated at least 3 times.
* Avoid encouraging [Pragmatists](The-Pragmatist.md) to belittle Designers. Abstractions have tremendous value. The reason why they become tedious usually has to do with changing requirements during early stages of the project. The longer the project runs, the more stable the codebase becomes, such that abstractions can add much more value as a means to design and document the code compared to e.g. inline comments.

## Edge cases - when is it ok?
* Abstractions are a powerful tool to manage complexity. They are especially useful in stable parts of the system, where they can help to manage complexity and to document the code.
* Typically, there are too few abstractions in a system, not too many. The Designer is a rare smell.

## Questions and Indications to identify a Designer
* What are your favourite things about software engineering? (Software Design, DDD, Refactoring, Clean Code, etc.)

## How does it happen?
* The Designer is often a person that has a strong affinity for design and architecture.
* They typically have issues reading low-level code and prefer to work on higher-level abstractions.

## Related Smells
* Opposite of [The Pragmatist](The-Pragmatist.md).
* Can result from [an Alumni](The-Alumni.md) due to their inherent affinity for design.
* Often also has the tendency to be [a Refactoring Master](The-Refactoring-Master.md).