# Ex No: 05 - Design & Implementation of 1-Bit Full Adder Using Cadence Virtuoso

## Aim
The aim is to design and implement a 1-bit Full Adder using Cadence Virtuoso and verify its functionality through transient analysis simulation.

## Tools Required
### Cadence Virtuoso Suite
- **Virtuoso Schematic Editor** (for circuit design)
- **Spectre Simulator** (for circuit simulation)

### Process Design Kit (PDK)
- CMOS technology library

### Computer System
- Minimum **4GB RAM** and a **multi-core processor**

## Procedure

### 1. Launch Cadence Virtuoso Environment:
- Open the **Cadence Virtuoso** tool and set up the working library.
- Create a new **schematic cell view** for the 1-bit Full Adder design.

### 2. Schematic Design:
- Select **NMOS and PMOS transistors** from the library.
- Construct the **Full Adder circuit** using **CMOS**.
- Connect the inputs (**A, B, Cin**) and outputs (**Sum, Cout**) properly.

### 3. Simulation:
- Check the design for **errors** and proceed with simulation.
- Launch the **Analog Design Environment (ADE)**.
- Perform **transient analysis** to verify the output logic.
- Set up **input stimulus** and analyze the **output waveform**.

## Circuit Diagram
![Screenshot 2025-03-28 193352](https://github.com/user-attachments/assets/08a3dce3-1de0-4f1e-b050-7c3569490edd)


## Truth Table for 1-Bit Full Adder
| A | B | Cin | Sum | Cout |
|---|---|-----|-----|------|
| 0 | 0 |  0  |  0  |  0   |
| 0 | 0 |  1  |  1  |  0   |
| 0 | 1 |  0  |  1  |  0   |
| 0 | 1 |  1  |  0  |  1   |
| 1 | 0 |  0  |  1  |  0   |
| 1 | 0 |  1  |  0  |  1   |
| 1 | 1 |  0  |  0  |  1   |
| 1 | 1 |  1  |  1  |  1   |

## Schematic Diagram
### 1. Schematic of 1-Bit Full Adder:
*(Schematic image to be inserted here)*

## Output
### Transient Analysis Output:
*(Simulation waveforms to be inserted here)*

## Results
1. Successfully designed the **1-bit Full Adder** schematic using **Cadence Virtuoso**.
2. Performed **transient analysis**, verifying the correct operation of the **Full Adder**.
3. Observed **correct logic switching behavior** in response to input signals.
