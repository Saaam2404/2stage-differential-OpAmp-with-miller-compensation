# Two-Stage CMOS Operational Amplifier Design (250 nm CMOS)

## Overview
This repository presents the complete design, analysis, and simulation of a two-stage CMOS operational amplifier implemented in a 250 nm CMOS technology using Tanner EDA. The project includes transistor-level design, hand calculations based on small-signal analysis, and verification through SPICE simulations.

The op-amp consists of:
- PMOS Differential Input Pair
- Active Current Mirror Load
- Common-Source Second Gain Stage
- Miller Compensation Capacitor
- Bias Current Mirror Network

---

## Features

- Two-stage CMOS operational amplifier
- PMOS differential input stage
- Active current mirror load
- Common-source second stage
- Miller compensation for frequency stability
- Designed in 250 nm CMOS technology
- Complete theoretical analysis
- SPICE simulation verification

---

## Design Specifications

| Parameter | Value |
|-----------|---------|
| Technology | 250 nm CMOS |
| Supply Voltage | ±2.5 V |
| Compensation Capacitor | 1 pF |
| Bias Current | 50 µA |

---

## Simulated Performance

| Parameter | Result |
|-----------|---------|
| Open Loop Gain | ~45 dB |
| 3-dB Bandwidth | ~102 kHz |
| Gain Bandwidth Product | ~27 MHz |
| Phase Margin | ~63° |
| Output Swing | ≈ ±2.2 V (linear region) |
| Common Mode Gain | Verified |
| CMRR | Verified |
| Slew Rate | Measured from transient simulation |

---

## Analysis Performed

### DC Analysis
- Operating Point
- Device Bias Verification
- Output Swing
- Input Common Mode Range (ICMR)

### Small-Signal Analysis
- Differential Gain
- Common Mode Gain
- Common Mode Rejection Ratio (CMRR)
- Input and Output Resistance

### Frequency Response
- Bode Plot
- Dominant Pole
- Non-Dominant Pole
- Gain Bandwidth Product (GBW)
- Phase Margin
- Miller Compensation Analysis

### Transient Analysis
- Slew Rate Measurement
- Large Signal Response
- Unity Gain Buffer Verification

---

## Theory Verified

The following analytical expressions were verified using simulation:

- Differential Gain
- Common Mode Gain
- Output Resistance
- Gain Bandwidth Product
- Dominant Pole Frequency
- Phase Margin
- CMRR
- Slew Rate

---

## Software Used

- Tanner EDA 2019
- T-Spice
- S-Edit

---

