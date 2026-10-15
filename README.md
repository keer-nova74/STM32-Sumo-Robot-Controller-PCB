STM32 Sumo Robot Controller PCB

Overview

This project focuses on designing a custom Printed Circuit Board (PCB) for an autonomous sumo robot using KiCad. The controller is intended to integrate a microcontroller, motor drivers, sensor interfaces, and power management into a compact robotics hardware platform.

Project Status: In Progress

Planned Features

- STM32 microcontroller interface for robot control
- Dual DC motor driver circuit
- Infrared sensor interfaces for opponent and boundary detection
- Battery power input and distribution
- Voltage regulation for logic and peripheral circuits
- Motor and sensor connectors
- Programming and debugging interface
- Compact PCB layout suitable for a sumo robot chassis

Hardware Design

The PCB design will be developed around the following functional blocks:

Block| Purpose
Microcontroller| Executes robot control logic
Motor driver| Controls the direction and speed of two DC motors
Infrared sensors| Supports opponent detection and ring-boundary detection
Power management| Supplies appropriate voltages to the controller and peripherals
Communication and debugging| Provides access for programming and troubleshooting
Expansion connectors| Allows additional sensors and peripherals to be connected

Final components and circuit specifications will be confirmed during the design process.

Design Tools

- KiCad — schematic capture and PCB layout
- GitHub — version control and project documentation

Design Workflow

1. Define system requirements and select suitable components.
2. Create the circuit schematic in KiCad.
3. Assign footprints and verify component pinouts.
4. Perform Electrical Rules Check (ERC).
5. Arrange components and route PCB tracks.
6. Perform Design Rules Check (DRC).
7. Review power distribution, grounding, and connector placement.
8. Generate Gerber and drill files after validating the design.

Learning Objectives

- Understand microcontroller-based robotics hardware.
- Learn motor-driver integration and power distribution.
- Practise schematic design and PCB routing in KiCad.
- Understand component footprints and electrical design rules.
- Develop good PCB documentation and design-review practices.

Project Deliverables

The repository will contain the following files as the design progresses:

- KiCad schematic (".kicad_sch")
- KiCad PCB layout (".kicad_pcb")
- KiCad project file (".kicad_pro")
- Bill of Materials (BOM)
- PCB layout screenshots
- Gerber and drill files after design validation

Current Status

The project is currently in the planning and design stage. Components, schematic connections, PCB routing, and electrical checks will be completed and documented as development progresses.

Future Improvements

- Optimise component placement and board dimensions.
- Improve power routing and grounding.
- Add suitable protection for power and external interfaces.
- Validate the schematic and PCB using ERC and DRC.
- Document design decisions and revisions.

Author's Notes

This project is intended to develop practical skills in PCB design, embedded hardware, and robotics electronics. Design decisions and improvements will be documented as the project develops.
