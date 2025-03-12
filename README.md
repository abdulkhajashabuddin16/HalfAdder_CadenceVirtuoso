# This repository contains the Half Adder Design using Cadence Virtuoso

## Overview
This repository contains the design and simulation files for a **Half Adder** implemented using **Cadence Virtuoso**. The project includes schematic design, layout, verification, and transient analysis.

## Files

- ***`HALFADDER_SCH.png`*** – Schematic diagram of the half-adder
- ***`HALFADDER_SCH1.png`*** – Additional schematic view
- ***`HALFADDER_LAYOUT.png`*** – Layout design of the half-adder
- ***`HALFADDER_LVS.png`*** – Layout Versus Schematic (LVS) verification results
- ***`HALFADDER_DRC.png`*** – Design Rule Check (DRC) results
- ***`HALFADDER_RC.png`*** – Resistor-Capacitor extraction results
- ***`HALFADDER_TB.png`*** – Test bench setup for simulation
- ***`HALFADDER_Trans-Analys.png`*** – Transient analysis results
- ***`LAYOUT.png`*** – Additional layout visualization

## Requirements
- ***Cadence Virtuoso*** (for schematic and layout design)
- ***Spectre Simulator*** (for transient analysis)

 ## Simulation and Verification
- **Schematic Design**: Designed and verified using Cadence Virtuoso.
- **Layout Design**: Implemented in Virtuoso Layout Editor.
- **LVS & DRC Checks**: Ensured layout correctness and design rule compliance.
- **RC Extraction**: Analyzed parasitic effects in the layout.
- **Transient Analysis**: Simulated output waveforms to verify correct operation.

# Schematic design
![image](https://github.com/abdulkhajashabuddin16/HalfAdder_CadenceVirtuoso/blob/main/HALFADDER_SCH1.png)

### Truth Table
| Input A | Input B | Sum (S) | Carry (C) |
|---------|---------|---------|-----------|
| 0       | 0       | 0       | 0         |
| 0       | 1       | 1       | 0         |
| 1       | 0       | 1       | 0         |
| 1       | 1       | 0       | 1         |

# Transient Analysis Result
![image](https://github.com/abdulkhajashabuddin16/HalfAdder_CadenceVirtuoso/blob/main/HALFADDER_Trans-Analys.png)
