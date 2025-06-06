# The Flow of the Design

1. Specification
2. Feature Design
    - List of features with detailed descriptions about f.e. algorithms, UX etc.
3. Design Implementation
    - Source code / Schematics / HDLs
4. Design Implementation Tests
    - Software requires Unit and Fragment testes
    - Schematics and HDLs requires Simulations
5. Design Implementation Testbench
    - Integration tests, e2e, debug and telemetry data aquisition
6. Production Implementation
    - In case of software it meant having a build without unneccesary testing and development features
    - In case of hardware it meant designing a fabricable, physical design
7. Production Implementation Tests:
    - Software requires Unit and Fragment testes
    - Physical Hardware design requires Simulations
8. Production Implementation Testbench:
    - Integration tests, e2e, debug and telemetry data aquisition
9. Design Distribution:
    - Software requires deployment and devops setup
    - Hardware requires prepearation of manufacturing files
