# FlexSoC – Modular Prototyping Platform

**FlexSoC** is an open hardware **carrier + compute module** system for rapid prototyping 
in **automotive, industrial, and medical** domains.

## 🔑 Features
- Universal carrier board with wide-input power (9–36 V)
- Isolated CAN-FD, RS-485, Ethernet, USB-C, microSD, and expansion sockets
- Replaceable compute modules: SoC-FPGA (Xilinx Zynq), RP2040, ESP32, STM32, i.MX, etc.
- Standard **UCM-120 pinout** for future modules
- Open-source schematics, PCB, firmware, and mechanical designs

## 📂 Repository Structure
- `docs/` – Specifications, pinouts, compliance notes
- `hardware/` – Carrier & compute module schematics, PCB, BOM
- `firmware/` – Example firmware & FPGA stubs
- `software/` – CLI tools and BSP overlays
- `mechanical/` – STEP/SCAD models for enclosures
- `tests/` – Boundary-scan and bring-up scripts

## 🛠️ Tools Used
- [KiCad](https://www.kicad.org/) for hardware design
- [FreeRTOS](https://www.freertos.org/) and [Zephyr](https://zephyrproject.org/) for MCUs
- [Yocto Project](https://www.yoctoproject.org/) for Linux SoCs
- Python for test utilities

