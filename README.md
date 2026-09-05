# Water Level Alarm PCB

A custom **Water Level Alarm PCB** designed using **KiCad** for detecting water levels and providing an alarm indication when the water reaches the required level.

This repository contains the PCB design documentation, schematic, PCB layout views, 3D visualizations, design verification results, and Gerber manufacturing files.

---

## 📌 Project Overview

The **Water Level Alarm PCB** is a custom-designed printed circuit board intended for a water level monitoring and alarm system.

The PCB design was created using **KiCad**, including the schematic design, PCB layout, board visualization, and manufacturing file generation.

The repository provides all the necessary design and fabrication-related files in an organized structure.

---

## 🎯 Project Objective

The main objective of this project is to design a dedicated PCB for a water level alarm system.

The PCB is intended to:

- Provide a dedicated circuit board for the water level alarm system.
- Organize the electronic components and electrical connections.
- Provide a compact PCB layout.
- Support PCB manufacturing through standard Gerber and drill files.
- Provide a complete KiCad-based design workflow.
- Allow the PCB design to be reviewed and fabricated from the provided manufacturing files.

---

## 🛠️ Design Tool

The PCB was designed using:

- **KiCad** – Electronic schematic and PCB design
- **Gerber Viewer** – Manufacturing file inspection and verification

---

## 📁 Repository Structure

```text
Pcb_Water_level/
│
├── DRC Clean_image.png
├── README.md
├── symbol_field_table.png
│
├── gerber_files/
│   ├── water_alaram-B_Cu.gbr
│   ├── water_alaram-B_Cu.zip
│   ├── water_alaram-B_Mask.gbr
│   ├── water_alaram-B_Silkscreen.gbr
│   ├── water_alaram-Edge_Cuts.gbr
│   ├── water_alaram-F_Cu.gbr
│   ├── water_alaram-F_Mask.gbr
│   ├── water_alaram-F_Silkscreen.gbr
│   ├── water_alaram-NPTH.drl
│   └── water_alaram-PTH.drl
│
├── pcb_views/
│   ├── 3d_view1.png
│   ├── 3d_view2.png
│   ├── 3d_view3.png
│   ├── All_layers.png
│   ├── Back_layer.png
│   ├── Front_layer.png
│   └── full_layer.png
│
└── schematic/
    └── schematic_view.png
