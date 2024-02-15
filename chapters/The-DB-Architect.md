# The DB Architect
## Explanation
* Uses Entity-Relationship Diagrams (ERD) instead of behavioural methods to describe a system.

## Why is it a problem?
* A system provides value through its behaviour, not solely through its data.
* Even though data is important, modelling a system based on the employed database paradigm, like SQL, couples it directly to the technology.
* Systems may not easily evolve if they are coupled to the underlying database scheme.

## How to fix it?
* Use behavioural methods like EventStorming or Event Modelling to describe the system from a business-domain perspective.
* Employ strategic Domain-Driven Design to model and split the system using bounded contexts and domain experts.
* Educate the DB Architect on newer methods and paradigms like DDD, EventStorming, etc.

## Edge cases - when is it ok?
* If the system is a pure CRUD application, it may be ok to use an ERD only.
* ERDs are a great tool to describe the database structure of a system if we use SQL, but they cannot adequately describe the behavior fo the system.

## Questions and Indications to identify a DB Architect
* What is the most important part in a software system?
* Can you show a diagram of the system?

## How does it happen?
* Old school, database-focused software engineering education without learning new methods over the years.
* Lack of Domain Modelling knowledge.
* "I have always done it that way!"

## Related Smells
* A DB Architect may often also show signs of [a Silverback](The-Silverback.md) and [a Threatened](The-Threatened.md)