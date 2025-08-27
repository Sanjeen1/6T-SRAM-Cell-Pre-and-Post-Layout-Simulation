# 6T-SRAM-Cell-Pre-and-Post-Layout-Simulation
Pre-layout and post-layout simulation of a 6T SRAM cell using open-source EDA tools. This project covers schematic design, SPICE simulation, physical layout in Magic VLSI, parasitic extraction, and verification. Includes waveform analysis for read/write operations, comparison between ideal (pre-layout) and realistic (post-layout with parasitics).

# 6T-SRAM-Cell-Pre-and-Post-Layout-Simulation

This repository contains the design, simulation, and verification of a **6T SRAM Cell** using open-source EDA tools.  
The project demonstrates the complete flow from schematic design to layout verification, including **pre-layout** and **post-layout simulations**.

---

## 📌 Project Overview

The 6T SRAM cell is one of the most fundamental building blocks in memory design.  
In this project, the following steps are carried out:

1. **Schematic Design**  
   - Creation of the 6T SRAM schematic.
   - Verification of read and write operations using **LTSpice/Ngspice**.

2. **Pre-layout Simulation**  
   - SPICE simulations performed without considering layout parasitics.
   - Captures the ideal behavior of the SRAM cell.

3. **Physical Layout Design**  
   - Layout created in **Magic VLSI** using **TSMC 180nm technology file**.
   - Ensures design rule correctness (DRC clean) and layout vs schematic check (LVS clean).

4. **Post-layout Simulation**  
   - Extraction of parasitics using Magic/Ngspice.
   - More realistic simulation considering wire and device parasitics.
   - Comparison of results with pre-layout simulations.

---

## 📂 Repository Contents

- **Layout/** → Contains the Magic VLSI layout files.  
- **Schematic Pre layout/** → Contains schematic and simulation setup for pre-layout analysis.  
- **6T-SRAM LTSPICE.pdf** → Pre-layout simulation results.  
- **6T-SRAM-Read & Write.pdf** → Detailed analysis of read/write operations.  
- **Ngspice post layout simulation.jpg** → Post-layout simulation waveform.  
- **Pre layout simulation_LTSPICE.jpg** → Pre-layout simulation waveform.  
- **Schematic_Write.pdf** → Write operation schematic reference.  
- **tsmc180nm.txt** → Technology model file for simulation.  

---

## 🖼️ Results and Screenshots

### 🔹 Layout of 6T SRAM Cell
*(Upload screenshot of layout here)*  
![Layout Screenshot](PLACEHOLDER_LAYOUT_IMAGE)

---

### 🔹 Pre-layout Simulation Waveform
*(Upload pre-layout simulation waveform here)*  
![Pre-layout Simulation](PLACEHOLDER_PRELAYOUT_IMAGE)

---

### 🔹 Post-layout Simulation Waveform
*(Upload post-layout simulation waveform here)*  
![Post-layout Simulation](PLACEHOLDER_POSTLAYOUT_IMAGE)

---

## ⚙️ Tools Used

- **Magic VLSI** → Layout design and parasitic extraction.  
- **Ngspice / LTSpice** → Circuit simulations (pre-layout and post-layout).  
- **TSMC 180nm PDK** → Technology file used for device modeling.  

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/6T-SRAM-Cell-Pre-and-Post-Layout-Simulation.git
