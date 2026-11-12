# How I work

## DesignFlow

### The Flow of the Design

1. Specification
2. Feature Design
    - List of features with detailed descriptions about f.e. algorithms, UX etc.
3. Design Implementation
    - Source code / Schematics / HDLs
4. Design Implementation Tests
    - Software requires Unit and Fragment tests
    - Schematics and HDLs require Simulations
5. Design Implementation Testbench
    - Integration tests, e2e, debug and telemetry data acquisition
6. Production Implementation
    - In case of software it meant having a build without unnecessary testing and development features
    - In case of hardware it meant designing a fabricable, physical design
7. Production Implementation Tests:
    - Software requires Unit and Fragment tests
    - Physical Hardware design requires Simulations
8. Production Implementation Testbench:
    - Integration tests, e2e, debug and telemetry data acquisition
9. Design Distribution:
    - Software requires deployment and devops setup
    - Hardware requires preparation of manufacturing files

## CodeOfDesign

### The Code of Design

- The design has to be functional
- The design has to be optimal
- The design should have as many abstractions as needed for achieving better readability
- The design should assume testing and validation (verification) methods before it will be synthesized
- Testbenches should be mandatory
- The internal structure should be described; the outer usage should be documented carefully
- Every external dependency needed to perform synthesis of the design should be documented and described with detailed information of origin
- Design should implement methods for performing runtime telemetry and debugging solutions if possible

## CodeOfCode

### The Code of Code

- The code has to work
- The code has to be efficient (balance resource usage)
- Simple abstractions are the key of readability
- Pick needed features from each language used and stick to them
- Tests, tests and again, tests
- Use static analysis tools
- Document external API and features (API Reference), describe internal structure
- Tools are the dependencies
- Every external dependency needed for project assembly should be specified with detailed information of origin
- 3rd party infrastructure dependencies should be wrapped in internal API
- One or more runtime debugging and telemetry solutions like logging, metrics, traces etc. should be implemented

## TestingLore

### The lore of the Tests

- Unit tests: The sm0l ones; typically covers single units of design, f.e. design schematic or description or single function / procedure
- Fragment tests: Cover whole module (whatever it means); one level of complexity up in relation to Unit tests
- Integration tests: Tests that are embedded in a design
- E2E (End to End) tests: Cover testing end (usage) layer of design
