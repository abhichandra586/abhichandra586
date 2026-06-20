<div align="center">

# Abhi Chandra B

**B.Tech ECE · 3rd Year · Vignan's Institute of Information Technology, Visakhapatnam**

Building a complete VLSI design portfolio from first principles —
logic gates → combinational → sequential → FSMs → 16-bit pipelined RISC processor

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/abhi-chandra-b-8ab791413)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:24l31a0436@vignaniit.edu.in)

</div>

---

## About Me

I'm a 3rd-year B.Tech ECE student (CGPA: 9.68) specialising in RTL design and digital verification. My primary focus is building a structured, self-directed VLSI portfolio — 8 repositories that form a continuous build from AND gates up to a full 5-stage pipelined RISC processor in Verilog. I also work on embedded systems projects and am preparing for GATE ECE 2027 in parallel.

---

## VLSI Portfolio — 8-Step Roadmap

> A single structured build: each repo feeds directly into the next, culminating in a 16-bit pipelined RISC processor on FPGA.

| # | Repository | Status | Contents |
|---|-----------|--------|----------|
| 01 | [basic-logic-gates](https://github.com/abhichandra586/01-basic-logic-gates) | ✅ Complete | AND, OR, NOT, NAND, NOR, XOR, XNOR — with testbenches and GTKWave waveforms |
| 02 | [combinational-circuits](https://github.com/abhichandra586/02-combinational-circuits) | ✅ Complete | Adders, MUX, Decoder, Encoder, Comparator, 16-bit ALU — Yosys synthesis + GLS |
| 03 | [sequential-circuits](https://github.com/abhichandra586/03-sequential-circuits) | ✅ Complete | Flip-Flops, Registers, Counters, Shift Registers, Synchronous SRAM 256×16 |
| 04 | [finite-state-machines](https://github.com/abhichandra586/04-finite-state-machines) | 🔨 In Progress | Moore FSM, Mealy FSM, Traffic Light Controller, 1011 Sequence Detector, UART, SPI, Debounce |
| 05 | 05-alu-16bit | ⏳ Upcoming | SystemVerilog ALU + Formal Assertions + Synthesis |
| 06 | 06-processor-components | ⏳ Upcoming | PC, Control Unit, Register File, Hazard Unit |
| 07 | 07-risc16-pipelined-processor | ⏳ Upcoming | Complete 5-stage pipelined RISC processor |
| 08 | 08-protocols-and-interfaces | ⏳ Upcoming | UART, SPI, AXI4-Lite in SystemVerilog |

---

## Featured Projects

### 🔷 [01 — Basic Logic Gates](https://github.com/abhichandra586/01-basic-logic-gates)
All 7 fundamental gates (AND, OR, NOT, NAND, NOR, XOR, XNOR) implemented in Verilog from scratch, each with a dedicated testbench and GTKWave waveform verification against complete truth tables.
`Verilog` · `Icarus Verilog` · `GTKWave`

---

### 🔷 [02 — Combinational Circuits](https://github.com/abhichandra586/02-combinational-circuits)
17 circuits from half-adder to a full 16-bit ALU, including a 16-bit Ripple Carry Adder, Adder-Subtractor, Magnitude Comparator, and priority encoders. Three key modules (Full Adder, 16-bit Adder-Subtractor, 16-bit ALU) synthesised with **Yosys** and verified via gate-level simulation.
`Verilog` · `Icarus Verilog` · `GTKWave` · `Yosys` · `Graphviz`

---

### 🔷 [03 — Sequential Circuits](https://github.com/abhichandra586/03-sequential-circuits)
All major sequential building blocks: D/T/JK/SR flip-flops, 4-bit and 16-bit registers, up/up-down/BCD/Gray code counters, all four shift register modes (SISO/SIPO/PISO/PIPO), and a 256×16 synchronous SRAM — the same SRAM that becomes the data memory stage in the final processor.
`Verilog` · `Icarus Verilog` · `GTKWave`

---

### 🔷 [04 — Finite State Machines](https://github.com/abhichandra586/04-finite-state-machines) *(In Progress)*
Moore and Mealy FSMs, Traffic Light Controller, 1011 Sequence Detector, UART Transmitter, UART Receiver, SPI Master, and Debounce Circuit — all in Verilog with simulation-verified waveforms.
`Verilog` · `Icarus Verilog` · `GTKWave`

---

### 🔧 [Verilog EDA Automation](https://github.com/abhichandra586/verilog-eda-automation)
A Python CLI framework for RTL regression testing: auto-compiles Verilog with `iverilog`, runs simulations, parses PASS/FAIL results, and generates an HTML dashboard and JSON report. Supports watch mode, tag-based test filtering, Vivado synthesis report parsing, and CI/CD integration. Built with collaborator Sujeet Kona.
`Python` · `Icarus Verilog` · `watchdog` · `Vivado`

---

### 📚 [HDLBits Practice](https://github.com/abhichandra586/verilog-hdlbits)
Structured Verilog problem-solving on HDLBits, running in parallel with the 8-repo VLSI portfolio.
`Verilog` · `HDLBits`

---

## Upcoming Projects

### 📡 CubeSat Telemetry System *(repo coming soon)*
Real-time environmental and inertial data acquisition with wireless downlink, simulating a CubeSat ground-link scenario. Uses LoRa at 433 MHz for 2km+ range communication.
**Hardware:** ESP32, INA219, BMP280, DHT11, MPU6050, SX1278 LoRa · **Skills:** Embedded C, SPI, I2C, PCB design

---

### 🤖 AuraGlove — Gesture Recognition Glove *(repo coming soon)*
A wearable glove that maps hand gestures to commands using flex sensors and an IMU.
**Hardware:** Flex sensors, IMU, microcontroller · **Skills:** Signal processing, embedded firmware, hardware prototyping

---

## Skills & Tools

**Hardware Description**

![Verilog](https://img.shields.io/badge/Verilog-HDL-blue?style=flat)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-HDL-blueviolet?style=flat)
![RTL Design](https://img.shields.io/badge/RTL-Design-informational?style=flat)

**Simulation & Synthesis**

![Icarus Verilog](https://img.shields.io/badge/Icarus-Verilog-brightgreen?style=flat)
![GTKWave](https://img.shields.io/badge/GTKWave-Waveform%20Viewer-green?style=flat)
![Yosys](https://img.shields.io/badge/Yosys-Synthesis-yellow?style=flat)
![Vivado](https://img.shields.io/badge/Vivado-FPGA-red?style=flat)

**Embedded Systems**

![ESP32](https://img.shields.io/badge/ESP32-Embedded-orange?style=flat)
![C/C++](https://img.shields.io/badge/C%2FC%2B%2B-Language-lightgrey?style=flat)
![LoRa](https://img.shields.io/badge/LoRa-RF-9cf?style=flat)

**Tooling**

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white)

---

## GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=abhichandra586&show_icons=true&theme=github_dark&hide_border=true&count_private=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=abhichandra586&layout=compact&theme=github_dark&hide_border=true)

[![GitHub Streak](https://streak-stats.demolab.com?user=abhichandra586&theme=github-dark&hide_border=true)](https://git.io/streak-stats)

</div>

---

## Currently

- 🔨 Building Repo 4 — Finite State Machines (Moore, Mealy, UART, SPI Master, Debounce)
- 📖 GATE ECE 2027 preparation running in parallel
- 🎯 Target: complete 16-bit pipelined RISC processor by October 2026

---

<div align="center">

*Building from AND gate to a 16-bit pipelined RISC processor — one module at a time.*

</div>
