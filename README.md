# Booh RP2040

A minimal, RP2040-based Pi Pico clone, designed and built from scratch in KiCad.

<img width="468" height="556" alt="Screenshot 2026-07-04 223909" src="https://github.com/user-attachments/assets/a4ed8ba3-658d-4e78-99b9-0bf823aafedb" />


## Overview

Booh RP2040 is a custom development board built around the Raspberry Pi RP2040 microcontroller.This repo covers schematic capture, PCB layout, and assembly for a minimal Pico-style board.

## Specs

- **MCU:** Raspberry Pi RP204
- **Flash:** W25Q16JV, 2MB QSPI flash
- **Power:** USB-C input, regulated to 3.3V via onboard LDO
- **I/O:** through-hole pin headers along both edges
- **Layout:** 2-layer PCB with groud layer
- **Form factor:** Pi Pico-sized footprint

## Repo Contents

- `kicad/` — KiCad schematic and PCB layout files
- `gerbers/` — Gerber files for manufacturing
- `bom/` — Bill of materials

## Getting Started

1. Order the PCB using the Gerber files in `gerbers/` (JLCPCB, PCBWay, etc.)
2. Source components using the BOM in `bom/`
3. Assemble and Solder by hand to obtain new skillz
4. Flash with MicroPython, CircuitPython, or the Pico SDK like a standard RP2040 board
