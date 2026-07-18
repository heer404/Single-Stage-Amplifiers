# CMOS Single-Stage Amplifiers

A comprehensive collection of **CMOS single-stage amplifier** designs implemented and simulated in **Cadence Virtuoso**. This repository includes different amplifier configurations and load types, along with their circuit schematics and simulation results for performance comparison.

---

## Overview

Single-stage amplifiers are the fundamental building blocks of analog integrated circuits. This repository explores the design and analysis of various CMOS single-stage amplifier topologies, highlighting their gain characteristics, output behavior, and the effect of different load configurations.

The circuits are designed and simulated using **Cadence Virtuoso** and **Spectre** using technology gpdk180.

---

## Amplifier Configurations

The repository includes the following amplifier topologies:

- Common Source (CS)
- Common Gate (CG)
- Common Drain (CD / Source Follower)

Each topology is implemented with different load configurations, such as:

- Resistive-Load/
- Diode-Connected-Load/
- Current-Source-Load/
- PMOS-Active-Load/
- Source-Degenration/


---

## Simulation Results

Each amplifier includes:

- Circuit schematic
- AC analysis
- Voltage gain (V/V)
- Gain (dB)
- Performance comparison

---

## Repository Structure

```text
Single-Stage-Amplifiers/
│
├── Common-Source/
│   ├── Resistive-Load/
│   ├── Diode-Connected-Load/
│   ├── Current-Source-Load/
│   ├── PMOS-Active-Load/
│   └── Source-Degenration/
│
├── Common-Gate/
│   ├── Resistive-Load/
│   └── Current-Mirror-Load/
│
├── Common-Drain/
│   ├── Resistive-Load/
│   └── Current-Mirror-Load/
│
└── README.md
```

---

## Tools Used

- Cadence Virtuoso
- Cadence Spectre
- CMOS Process Design Kit (PDK): gpdk180

---

## Objectives

- Study the operation of CMOS single-stage amplifiers.
- Compare different amplifier topologies.
- Analyze the impact of various load configurations.
- Evaluate voltage gain and frequency response.
- Build a reference repository for analog CMOS circuit design.

---

## Future Work

- DC operating point analysis
- Transient analysis
- Noise analysis
- Power consumption comparison
- Gain-bandwidth comparison
- Layout implementation
- Post-layout simulations

---

## License

This repository is intended for educational and research purposes.
