---
permalink: /projects/
title: "Projects"
author_profile: true
---

## 64-bit APB Timer IP Core with Interrupt

Designed and verified a 64-bit APB Timer IP core with interrupt.

- Implemented an APB slave register map (12-bit address, 4 KB space) with control/status registers.
- Built a 64-bit count-up timer with a programmable divider (up to 256).
- Added compare-match interrupt generation with a maskable interrupt.
- Supported advanced features including debug halt/resume, wait-state insertion and byte access.

<b>Keywords</b>: Verilog, SystemVerilog, AMBA APB, self-checking testbench

## Wearable Fall-Detection Device (Student Research, 2026-2027)

A wearable device that detects falls and raises a local and Wi-Fi alert.

- Gowin GW1NSR-LV4C SoC (hard ARM Cortex-M3 + FPGA fabric) on the KIWI 4K board.
- MPU6050 inertial sensor over I²C, buzzer alarm, Wi-Fi alert through an ESP AT modem.
- Firmware in C, custom logic in Verilog with simulation testbenches.
- Two-layer carrier PCB designed in KiCad.

<b>Keywords</b>: Verilog, C, Gowin EDA, Icarus Verilog, KiCad
