# Mars-Rover-Mission-Control
Task details:

Functional Requirements (FRs)
What the system must do.
FR-01: The rover shall receive commands from Mission Control and execute valid commands.
FR-02: The rover shall report its current position, battery level, temperature, and communication status.
FR-03: The system shall reject invalid or unauthorized commands.
FR-04: The rover shall enter Safe Mode within 3 seconds when battery temperature exceeds the critical threshold or battery capacity falls below the defined emergency level.
FR-05: Mission Control shall receive command execution status.
FR-06: The system shall record all commands and critical rover events with a timestamp and operator ID.
FR-07: The system shall continue operating despite temporary communication interruptions. (Note: While this sounds like a quality, it defines a specific behavior the system must perform, making it a functional requirement in this context).

Non-Functional Requirements (NFRs)
How the system performs its functions (constraints and quality attributes).
NFR-01: Command processing should normally complete within 5 seconds after a command is received by the rover. (Performance)
NFR-02: The system shall require authenticated and role-authorized operators before accepting rover commands.
NFR-03: The system must operate effectively despite limited communication bandwidth and a communication delay of several minutes. (Reliability/Constraint)
NFR-04: The system shall support at least 20 simultaneously connected rovers.
