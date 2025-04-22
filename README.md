# 32-bit Synchronous Counter - VLSI Project

## Project Overview


This project presents the complete design and simulation of a 32-bit synchronous counter implemented using custom-built JK flip-flops and NAND gate logic in 180nm CMOS technology. The work involves a bottom-up approach beginning from transistor-level design, optimization of logic gates, to full layout and simulation.

Using industry tools such as Mentor Graphics IC Station and HSPICE, the project focuses on transistor sizing, propagation delay optimization, and layout-versus-schematic (LVS) validation. Also leveraged a modular design strategy—first implementing NAND2 and NAND3 gates, then composing JK flip-flops, and finally cascading them to realize a fully functional 32-bit counter.

This hands-on project not only reinforces concepts taught in VLSI Design but also provides practical experience in digital layout design, timing analysis, and debugging complex circuits—laying a strong foundation for careers in semiconductor and IC design.

---

## Highlights

- Implemented in 180nm CMOS using λ = 0.1 µm
- Custom transistor sizing using HSPICE simulations
- Designed in Mentor Graphics IC Station and simulated with HSPICE
- Level-wise design:
  - Level 1: NAND gates
  - Level 2: JK Flip-Flop
  - Level 3: 32-bit Counter

---

## Challenges Faced

- Manual layout design and LVS errors in Mentor Graphics
- Clock skew and feedback loop issues
- Optimization difficulties due to feedback and sizing dependencies

---

## References

- [Flip-Flop Basics (ElectronicsForYou)](https://www.electronicsforu.com/technology-trends/learn-electronics/flip-flop-rs-jk-t-d)
- CMOS VLSI Design - Weste & Harris
- HSPICE MOSFET Models Manual
