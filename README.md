# CMOS 2-Input XNOR Gate Project

## Overview
This project involves the design, simulation, and analysis of a **CMOS 2-Input XNOR Gate** using **Cadence Virtuoso**. The XNOR gate is a fundamental digital logic gate that outputs a high signal when both inputs are either high or low, making it essential in combinational logic circuits.

## Software & Tools Used
- **Cadence Virtuoso** (for schematic capture, layout, and simulation)
- **Assura** (for DRC and LVS verification)
- **Analog Design Environment (ADE)** (for waveform analysis)

## Project Workflow
### Schematic Design
- Designed using **Virtuoso Schematic Editor**.
- Includes **six MOSFETs** (4 PMOS & 2 NMOS) arranged in a pull-up and pull-down network.
- Verified through **Transient analysis**.

### Layout Design
- Created using **Virtuoso Layout Editor**.
- Optimized for **area efficiency** and minimal parasitics.
- Design Rule Check (**DRC**) performed for layout validation.

### Layout Versus Schematic (LVS) Check
- Ensured the layout matches the schematic using **LVS**.

### Parasitic Extraction & Post-Layout Simulation
- Extracted layout using **Assura**.
- Post-layout simulation performed to analyze parasitic effects.

## Technical Specifications
- **Technology Node**: 90nm (as per design constraints)
- **Supply Voltage (VDD)**: 1V
- **Logic Operation**: XNOR (Y = NOT(A ⊕ B))

## Results & Observations
- **Schematic Simulation**: Verified correct XNOR logic functionality.
- **Layout Optimization**: Ensured minimal area and **DRC compliance**.
- **Post-Layout Simulation**: Observed deviations due to parasitic capacitance and resistance.

## Testing
- A separate **test folder** has already been created for verification and simulation.

## Reference Images
- **2_Input_XNOR_Schematic**

  ![Xnor_Schematic](https://github.com/user-attachments/assets/08160b8c-0050-44da-8757-e7b533b92fd1)

- **2_Input_XNOR_Test**

![Xnor_Test](https://github.com/user-attachments/assets/88c9235a-94be-4f2d-a857-1bd2eabcb175)

- **2_Input_XNOR_ADE**

![Xnor_ADE](https://github.com/user-attachments/assets/99fe0112-fba2-4e25-be45-c2db30325334)

---
*This project belongs to me and is intended for educational and research purposes only. It should not be used directly for other purposes without permission.*

