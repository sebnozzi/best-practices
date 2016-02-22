# Draft

* Working with legacy-code

* De-couple
* Defer (in responsibility)
  * Let another part of the code deal with it
  * Let another type deal with it
* Defer (in time; be asynchronous)

## Working environment

* Breaks
* Get enough sleep
* Productivity curve
* Pomodoro
* Interruptions
* Focus
* Meetings
* The daily stand-up.

## Codebase organisation

* Packaging (structure of codebase)
* Organize into modules
  * Better separation of concerns
  * Better parallelization in team
  * Better compilation / build times

### Functional Programming

* Don't mix computations from side-effects
 * Isolate side-effects
* Favor immutability
 * Immutable collections
 * Immutable DTOs
 * Pure functions
 * Don't throw exceptions, return values
* Encapsulate null

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

