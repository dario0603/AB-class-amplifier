# Class-AB Audio Amplifier

<p align="left">
  <a href="#"><img src="https://img.shields.io/badge/KiCad-Schematic-314CB0?style=flat&logo=kicad&logoColor=white" alt="KiCad"></a>
  <a href="#"><img src="https://img.shields.io/badge/LTspice-Simulation-blue?style=flat" alt="LTspice"></a>
  <a href="#"><img src="https://img.shields.io/badge/Status-Completed-success?style=flat" alt="Status"></a>
</p>

Design and simulation of a **Class-AB Audio Power Amplifier**. The circuit merges the linearity of Class-A amplifiers with the efficiency of Class-B topology, minimizing crossover distortion.

---

## Features & Specifications

* **Class-AB Architecture**: Complementary push-pull output stage designed to reduce harmonic distortion.
* **LTspice Simulations**: Frequency response analysis (Bode plot), output power delivery, and THD (Total Harmonic Distortion) evaluation.
* **KiCad Hardware Design**: Complete schematic capture and PCB layout for the power stage.
* **Thermal Stability**: Integrated biasing network to prevent thermal runaway.

---

## Repository Structure

```text
.
├── Spice/         # Simulation files (.asc, .plt) for input and power stages
├── KiCad/         # KiCad project (.kicad_sch, .kicad_pcb, footprints/symbols)
└── README.md      # Project documentation
