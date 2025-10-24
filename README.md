# Singlebody

A custom mechanical keyboard PCB designed in KiCad 7.

## Overview

Singlebody is an open-source keyboard circuit board project featuring a single-body (non-split) design. This repository contains all the necessary files for manufacturing and assembling the keyboard PCB.

## Repository Contents

- **Singlebody.kicad_pro** - KiCad project file
- **Singlebody.kicad_sch** - Schematic file containing the electrical design
- **Singlebody.kicad_pcb** - PCB layout file with component placement and routing
- **production/** - Manufacturing files (Gerbers, drill files, etc.) ready for PCB fabrication
- **Singlebody-backups/** - Automatic KiCad backup files

## Design Software

This project was created using **KiCad 7**. To view or modify the design files, you'll need:
- [KiCad 7](https://www.kicad.org/download/) or later

## Manufacturing

Production files for PCB fabrication are located in the `production/Singlebody_2024-02-24_15-04-56/` directory. These files can be sent directly to PCB manufacturers such as:
- JLCPCB
- PCBWay
- OSH Park
- Other PCB fabrication services

## Getting Started

1. Clone this repository
2. Open `Singlebody.kicad_pro` in KiCad 7
3. Review the schematic (`Singlebody.kicad_sch`) and PCB layout (`Singlebody.kicad_pcb`)
4. Export
