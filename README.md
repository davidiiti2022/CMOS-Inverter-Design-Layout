
# CMOS Inverter Design & Layout

## Overview
This project focuses on the schematic design, simulation, and custom layout of a CMOS inverter using Cadence Virtuoso in a 180nm CMOS technology node.

The inverter operates at a supply voltage of 1.8V. The design was verified through circuit simulation and physical verification to ensure correct functionality and layout compliance.

## Project Objectives
- Design a CMOS inverter using NMOS and PMOS transistors.
- Perform schematic design and functional verification.
- Create a custom layout using Cadence Virtuoso Layout XL.
- Perform Design Rule Check (DRC) and Layout Versus Schematic (LVS) verification using Siemens Calibre.

## Tools and Technologies
- **EDA Tool:** Cadence Virtuoso
- **Layout Editor:** Cadence Virtuoso Layout XL
- **Physical Verification:** Siemens Calibre
- **Technology Node:** 180nm CMOS
- **Supply Voltage:** 1.8V

## Design Description
A CMOS inverter is a fundamental digital circuit consisting of a PMOS transistor and an NMOS transistor.

- When the input is LOW, the PMOS transistor turns ON and the output becomes HIGH.
- When the input is HIGH, the NMOS transistor turns ON and the output becomes LOW.

The circuit provides logical inversion with low static power consumption under ideal steady-state switching conditions.

## Design Flow
1. Created the CMOS inverter schematic in Cadence Virtuoso.
2. Configured the design for the 180nm technology node and 1.8V supply.
3. Simulated the circuit to verify inverter functionality.
4. Designed the custom layout using Layout XL.
5. Performed DRC verification to check layout design-rule compliance.
6. Performed LVS verification to confirm consistency between the schematic and layout.

## Verification Results
- **Schematic Verification:** Checked inverter functionality through simulation.
- **DRC:** Achieved zero design-rule violations.
- **LVS:** Achieved zero layout-versus-schematic violations.

## Key Learning Outcomes
- CMOS transistor-level circuit design.
- Schematic-driven custom layout development.
- Understanding of NMOS and PMOS switching behavior.
- Physical verification using DRC and LVS.
- Familiarity with the analog and custom IC design workflow.

## Applications
- Basic CMOS logic circuits.
- Standard-cell design fundamentals.
- Building blocks for digital and mixed-signal integrated circuits.

## Author
**David Kumar**  
B.Tech, Electrical Engineering  
Indian Institute of Technology Indore
