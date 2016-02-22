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

* Code duplication
* Dependency injection
  * Be specific on your needs
* Packaging (structure of codebase)

* Organise codebase into modules
  * Better separation of concerns
  * Better parallelization in team
  * Better compilation / build times

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
 * Don't throw exceptions, return values

### Others

* Avoid null
* Too many parameters

### Concurrency

* Avoid primitive concurrency
* Avoid polling
* Avoid race-conditions
* Be reactive
* Futures / Promises
* Actors
* Distributed computing

### Architecture

* Onion / Hexagon
* Separate the core from the drivers
* Domains

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

## Testing

* Aim at max ROI / min TCO
* Code-coverage can be misleading
* Refactor often!
* Maintainability is king
* Isolate implementation details
* Mocking / stubbing
* Proper UI testing
  * Avoid
  * Test wiring
  * Test typical cases
  * Make them maintainable
* Unit-tests: DO NOT hit the DB!

## Sharpening the Saw

* Examples from other disciplines
  * Musicians
  * Scientists
  * Athletes
  * Actors
* Practice!
* Katas
* Coding Dojos
* Code Retreats
* Focus on learning, not on finishing
* Meetups
* Pairing


