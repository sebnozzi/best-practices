# Draft

## Clean Code

* Code duplication
* Tight coupling
* Dependency injection
  * Be specific on your needs
* Leaking Abstractions
* Don't mix responsibilities
 * Per function
 * Per class
* Code smell: lots of private functions
* Code smell: too large / too much
* Don't mix levels of abstraction

* Working with legacy-code

## Codebase organisation

* Packaging (structure of codebase)
* Organize into modules
  * Better separation of concerns
  * Better parallelization in team
  * Better compilation / build times

### Communicating Meaning

* Short methods / functions
* Short classes / modules / files
* Meaningful names
* Avoid long invocation chains
  * Describe intermediate steps
* Avoid primitive types
  * Create domain types 
  * 
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

### Architecture

* Onion / Hexagon
* Separate the core from the drivers
* Domains
* Separate core from UI
* Proper UI
  * Generic, reusable, UI components
  * UI Controllers
  * Adapters

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

