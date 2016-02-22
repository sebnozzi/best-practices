# Draft

## General Principles

* Clean over confusing
* Simple over complex
* Explicit over implicit
* Defined over open
* Small over big
* Homogeneous over heterogeneous
  * One over many (responsibilities)
* Less over more
* Direct over ambiguous
* Fast over slow (tests, feedback)
* Automatic over manual

## Clean Code

### Communicating Meaning

* Short methods / functions
* Short classes / modules / files
* Meaningful names
* Avoid long invocation chains
  * Describe intermediate steps

### Comments
  * Consider what can change
  * Don't document the obvious
  * Describe top-level intent
  * Maintainable comments
  * Convert comments into units of code

### Responsibilities

* Don't mix responsibilities
 * Per function
 * Per class
* Code smell: lots of private functions
* Code smell: too large / too much

### Levels of Abstraction

* Don't mix levels of abstraction
 
### Functional Programming

* Don't mix computations from side-effects
 * Isolate side-effects
* Favor immutability
 * Immutable collections
 * Immutable DTOs
 * Pure functions
 * Don't throw exceptions

### Others

* Avoid null
* Too many parameters

### Working in Teams

* Static Code Analyzers
* Commit Hooks
* Continuous Integration
* Conventions for git comments
* Managing branches (e.g. git flow)

* Versioning (e.g. semantic versioning)
* Deployment strategies
* Upgrade strategies

* Data migrations

* Estimation strategies

* Configuration strategies

* Scalability
* Monitoring
* Security

## Clean Tests

* Aim at max ROI / min TCO
* Code-coverage can be misleading
* Refactor often!
* Maintainability is king
* Isolate implementation details
* Mocking / stubbing



* Don't hit the DB!

## Sharpening the Saw

* Practice
* Katas
* Coding Dojos
* Code Retreats
* Meetups
* Pairing


