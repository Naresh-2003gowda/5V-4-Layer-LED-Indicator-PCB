# 5V 4-Layer LED Indicator PCB — KiCad 9

## 📌 Project Overview

This project is a complete **4-layer PCB design of a 5V LED Indicator circuit**, developed using **KiCad 9**.

The main objective of this project was to gain practical experience with the complete PCB development workflow — starting from circuit schematic design and progressing through footprint assignment, multilayer PCB configuration, component placement, routing, design verification, 3D inspection, and generation of fabrication outputs.

This project also provided hands-on experience with the differences between a basic 2-layer PCB workflow and designing a **4-layer PCB**, including working with internal copper layers.

---

## ⚡ Circuit Description

The board is designed around a simple 5V LED indication circuit.

### Main components

* **J1 — 2-pin connector:** 5V power input
* **C1 — 100µF capacitor:** Bulk filtering / supply stabilization
* **C2 — 100nF capacitor:** High-frequency supply decoupling
* **R1 — 330Ω resistor:** LED current limiting
* **D1 — LED:** Visual indication of the applied 5V supply

When the 5V supply is applied through the input connector, the LED illuminates through the 330Ω current-limiting resistor.

The combination of the **100µF bulk capacitor** and **100nF decoupling capacitor** provides filtering and supply decoupling around the circuit.

---

## 🛠️ PCB Design Workflow

### 1. Schematic Design

The circuit schematic was created using **KiCad 9 Schematic Editor**.

The schematic defines the electrical relationships between the 5V input, capacitors, resistor, LED, and ground connections.

### 2. Footprint Assignment

Appropriate PCB footprints were assigned to the schematic components so that they could be transferred to the PCB layout.

### 3. 4-Layer PCB Configuration

The PCB was configured as a **4-layer board** consisting of:

* **F.Cu** — Front copper
* **In1.Cu** — Internal copper layer 1
* **In2.Cu** — Internal copper layer 2
* **B.Cu** — Back copper

Additional fabrication layers such as solder mask, silkscreen, and board outline were also used as required.

### 4. Component Placement

Components were arranged on the PCB with consideration for:

* Electrical connectivity
* Routing requirements
* Component accessibility
* Board organization
* Overall PCB layout

### 5. PCB Routing

The required electrical connections were routed between the components while working with the multilayer PCB structure.

This provided practical experience with PCB traces, copper layers, vias, routing paths, and multilayer board connectivity.

---

## 🔍 Design Verification

After completing the PCB layout, the design was checked using KiCad's verification tools.

The final design achieved:

**DRC: 0 errors and 0 warnings**

The completed PCB was also inspected using the **KiCad 3D Viewer** to check the physical appearance, component placement, board outline, and overall layout.

---

## 🏭 Fabrication Outputs

After completing and verifying the PCB design, the required manufacturing files were generated.

### Generated files include:

* Gerber files for copper layers
* Gerber files for solder mask
* Gerber files for silkscreen
* Gerber file for the board outline
* Drill files for PCB holes

The generated fabrication outputs were subsequently checked using **KiCad Gerber Viewer**.

This completes the workflow from **electrical schematic → PCB layout → verification → fabrication files**.

---

## 💻 Software & Tools

**Software:**

* KiCad 9

**KiCad tools used:**

* Schematic Editor
* PCB Editor
* 3D Viewer
* Gerber Viewer
* PCB Design Rule Checker (DRC)

---

## 📚 Key Learning Outcomes

Through this project, I gained practical experience in:

* Schematic creation
* Electrical connectivity
* Component and footprint selection
* PCB component placement
* 4-layer PCB configuration
* Multilayer PCB routing
* Copper layer management
* PCB design verification
* DRC checking
* 3D PCB visualization
* Gerber file generation
* Drill file generation
* Gerber verification
* Understanding the PCB fabrication workflow

---

## 📂 Project Contents

The repository can contain the following project files:

```text
5V-4-Layer-LED-Indicator-PCB/
│
├── Schematic/
│   └── 5V_LED_Indicator.kicad_sch
│
├── PCB/
│   └── 5V_LED_Indicator.kicad_pcb
│
├── Gerber/
│   ├── Copper Layers
│   ├── Solder Mask
│   ├── Silkscreen
│   └── Edge Cuts
│
├── Drill/
│   └── Drill Files
│
├── Images/
│   └── PCB 3D View
│
└── README.md

---

## 🎯 Conclusion

This **5V 4-Layer LED Indicator PCB** project was developed as a practical step toward improving my PCB design and hardware development skills.

Although the circuit itself is simple, the project focuses on understanding the **complete PCB development process**, particularly the workflow involved in creating and verifying a 4-layer board and preparing it for fabrication.

It has strengthened my practical understanding of **KiCad, multilayer PCB design, routing, design verification, and PCB manufacturing outputs**, and provides a foundation for working on more complex hardware designs in future projects.
