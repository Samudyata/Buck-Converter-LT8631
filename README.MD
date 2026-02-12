# Buck Converter Design using LT8631 - ISRO Internship

![ISRO](https://img.shields.io/badge/ISRO-Internship-blue) ![OrCAD](https://img.shields.io/badge/Tool-OrCAD-green) ![LTspice](https://img.shields.io/badge/Simulation-LTspice-orange)

---

## Overview

This project presents the design and simulation of a **compact, thermally efficient DC-DC buck converter** developed during an internship at the **Indian Space Research Organization (ISRO)**. The converter targets high-current loads in satellite subsystems and instrumentation modules, with an emphasis on minimal EMI, optimized thermal performance, and aerospace-grade reliability.

---

## Design Specifications

| Parameter | Value |
|-----------|-------|
| Input Voltage | 9V - 18V |
| Output Voltage | 5V |
| Output Current | 3A |
| Efficiency | >90% |
| Output Ripple | <30mV |
| IC | LT8631 (Synchronous Step-Down) |

---

## Design Highlights

- **Copper Pour Optimization** -- Dedicated copper pours on power planes for effective heat sinking and low-impedance current paths.
- **Via Stitching** -- Thermal and ground vias stitched across the PCB to improve heat dissipation and reduce ground impedance.
- **Minimal EMI** -- Layout techniques and component placement designed to minimize electromagnetic interference, meeting aerospace EMC requirements.
- **Shielding** -- Proper shielding strategies applied to sensitive nodes to maintain signal integrity under high-current switching.

---

## Tools Used

- **OrCAD PCB Designer** -- Schematic capture and PCB layout design.
- **LTspice** -- Circuit simulation for transient analysis, efficiency estimation, and ripple characterization.
- **LT8631 Datasheet** -- [Analog Devices LT8631 Datasheet](https://www.analog.com/media/en/technical-documentation/data-sheets/lt8631.pdf)

---

## Learning Outcomes

- Professional PCB design practices for power electronics in aerospace applications.
- Thermal profiling and junction temperature optimization for high-current regulators.
- Efficiency optimization using real-world component specifications and layout constraints.
- End-to-end integration of simulation and physical layout in aerospace power system design.

---

## Author

**Samudyata Jagirdar**
sjagird1@asu.edu

---

## Acknowledgements

This project was completed as part of an internship at the **Indian Space Research Organization (ISRO)**. Sincere thanks to ISRO for providing the opportunity, guidance, and resources to work on aerospace power electronics.
