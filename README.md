# Daniel Ng

Electrical Engineering student at UBC focused on embedded systems, firmware, PCB design, and hardware testing.

- Portfolio: [danielng.pages.dev](https://danielng.pages.dev)
- LinkedIn: [linkedin.com/in/danielngEE](https://linkedin.com/in/danielngEE)
- Email: [daniel.whn@outlook.com](mailto:daniel.whn@outlook.com)

---

## About

I am an Electrical Engineering student at UBC with experience in embedded firmware, hardware bring-up, RF testing, and PCB design. My work focuses on building reliable low-level systems, from bare-metal firmware and microcontroller peripherals to analog front ends and lab validation.

I previously worked as a Hardware Test Intern at Norsat International, where I supported RF characterization and troubleshooting of Ku-band hardware. I am currently leading the electrical and firmware development of a laser timing system for UBC Formula Racing.

---

## Technical Skills

**Programming:** C, C++, Python, A51 Assembly, RISC-V Assembly  
**Embedded Systems:** STM32, ESP32, EFM8, 8051, RISC-V, bare-metal firmware  
**Protocols:** I2C, SPI, UART, CAN, USB, RS-485, ESP-NOW  
**PCB & Hardware:** Altium Designer, analog front ends, ADCs, comparators, power systems  
**Lab Equipment:** Oscilloscopes, VNAs, RF signal analyzers, multimeters, soldering/rework  

---

## Projects

### UBC Formula Racing — Laser Timing System

End-to-end laser timing system for lap timing and speed measurement during vehicle testing.

- Designed a 3.3 V analog front end using photodiode sensing, transimpedance amplification, and comparator-based digital output
- Implemented ESP32-based wireless communication using ESP-NOW
- Worked on noise reduction, hysteresis tuning, beam-break detection, and reliable timing capture
- Designed the system for practical test-day use with optomechanical alignment and ambient-light rejection in mind

[GitHub](https://github.com/danielwhn25/FUBC-timing-gates)

---

### Digital Multimeter — STM32L051

Bare-metal embedded system for measuring resistance, voltage, frequency, capacitance, and inductance.

- Wrote embedded C firmware for ADC sampling, timers, LCD output, buttons, and serial communication
- Used timer capture for frequency measurement
- Built modular drivers for peripherals and user interface control
- Used Makefiles for project build and organization

[GitHub](https://github.com/danielwhn25/ELEC291_labs/tree/main/DMM_STM32LO51)

---

### Reflow Oven Controller — 8052 Microcontroller

Bare-metal thermal control system written in A51 assembly.

- Implemented a finite-state machine for reflow temperature profiles
- Used PWM control with temperature feedback
- Added NEC IR remote decoding, LCD output, and UART telemetry
- Validated temperature behavior with live plotting and lab testing

[GitHub](https://github.com/danielwhn25/4C11IV)

---

## Experience

### Hardware Test Intern — Norsat International

Worked on RF hardware testing and troubleshooting for Ku-band systems.

- Performed RF characterization using VNAs, RF signal analyzers, and lab test fixtures
- Supported testing of gain, saturation, spurious emissions, IMD, and noise performance
- Assisted with PCB-level inspection, rework, and troubleshooting
- Used schematics and measurements to identify hardware issues in RF signal paths and bias circuitry

---

## Currently Learning

- FreeRTOS on ESP32 and ARM Cortex-M
- PCB bring-up and power-system design
- More structured firmware architecture for embedded projects
