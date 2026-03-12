<div align="center">

<!-- HEADER BANNER -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:00b4d8,100:0077b6&height=200&section=header&text=Daniel%20Ng&fontSize=70&fontColor=ffffff&fontAlignY=38&desc=Electrical%20Engineer%20%7C%20Embedded%20Systems%20%7C%20Firmware&descAlignY=58&descSize=20&animation=fadeIn" />

<!-- TYPING ANIMATION -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=3500&pause=800&color=00B4D8&center=true&vCenter=true&multiline=false&width=700&lines=Bare-metal+firmware+%26+FPGA+development;RF+%26+hardware+test+%40+Norsat;UBC+Formula+Racing+%E2%80%94+Electrical+%26+Firmware+Lead;CAN+%7C+SPI+%7C+I%C2%B2C+%7C+UART+%7C+ESP32+%7C+8051;BASc+Electrical+Engineering+%40+UBC" alt="Typing SVG" />
</a>

<br/>

<!-- QUICK STATS BADGES -->
![Profile Views](https://komarev.com/ghpvc/?username=danielwhn25&color=00b4d8&style=flat-square&label=Profile+Views)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/danielngEE)
[![Portfolio](https://img.shields.io/badge/Portfolio-00b4d8?style=flat-square&logo=vercel&logoColor=white)](https://danielng.pages.dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:daniel.whn@outlook.com)

</div>

---

## ⚡ About Me

```c
/* daniel_ng.h */
#ifndef DANIEL_NG_H
#define DANIEL_NG_H

typedef struct {
    char*  name        = "Daniel Ng";
    char*  school      = "UBC Electrical Engineering (BASc, Co-op)";
    char*  role        = "Electrical & Firmware Lead @ UBC Formula Racing";
    char*  prev_exp    = "Hardware Test Intern @ Norsat";
    char*  focus[]     = { "Bare-metal Firmware", "FPGA Design",
                           "RF Systems", "Embedded IoT", "PCB Design" };
    bool   open_to     = INTERNSHIPS | COLLAB | OPEN_SOURCE;
    char*  email       = "daniel.whn@outlook.com";
} Engineer;

#endif /* DANIEL_NG_H */
```

---

## 🛠️ Tech Stack

<div align="center">

### Languages & Low-Level
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-004482?style=for-the-badge&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/A51%20Assembly-6E4C13?style=for-the-badge&logo=assemblyscript&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-CC0000?style=for-the-badge&logo=xilinx&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

### Embedded & Protocols
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![8051](https://img.shields.io/badge/8051%20MCU-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![FPGA](https://img.shields.io/badge/FPGA-DE10--Lite-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![I2C](https://img.shields.io/badge/I²C-444444?style=for-the-badge&logoColor=white)
![SPI](https://img.shields.io/badge/SPI-444444?style=for-the-badge&logoColor=white)
![UART](https://img.shields.io/badge/UART-444444?style=for-the-badge&logoColor=white)
![CAN](https://img.shields.io/badge/CAN%20Bus-FF6600?style=for-the-badge&logoColor=white)
![USB](https://img.shields.io/badge/USB-5C2D91?style=for-the-badge&logo=usb&logoColor=white)

### EDA / Design Tools
![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)
![Quartus](https://img.shields.io/badge/Quartus%20Prime-0071C5?style=for-the-badge&logo=intel&logoColor=white)
![ModelSim](https://img.shields.io/badge/Questa%2FModelSim-00427E?style=for-the-badge&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### Lab Equipment
![VNA](https://img.shields.io/badge/Vector%20Network%20Analyzer-8B0000?style=for-the-badge&logoColor=white)
![Oscilloscope](https://img.shields.io/badge/Oscilloscope-1A1A2E?style=for-the-badge&logoColor=white)
![SMT](https://img.shields.io/badge/SMT%2FTHT%20Soldering-5C4033?style=for-the-badge&logoColor=white)
![RF](https://img.shields.io/badge/RF%20Signal%20Analyzer-006400?style=for-the-badge&logoColor=white)

</div>

---

## 🚀 What I'm Building

<table>
<tr>
<td width="50%" valign="top">

### 🏎️ UBC Formula Racing — Laser Lap Timer
**Firmware Lead & System Architect**

Building a laser-based speed & lap timing system for a Formula SAE racecar:
- Custom **3.3V CMOS analog front end** with optomechanical shrouding
- **ESP-NOW** wireless link between master/slave **ESP32-S3** MCUs
- Photodiode TIA noise characterization → adjustable hysteresis for **20 dB SNR**, **BER < 10⁻⁷**

`ESP32-S3` `ESP-NOW` `Analog Front End` `Wireless` `C`

</td>
<td width="50%" valign="top">

### ♨️ Oven Reflow Controller
**Bare-Metal FPGA Firmware**

Deterministic thermal control system on a **CV-8052 soft-core** (DE10-Lite):
- FSM with adaptive **PWM closed-loop** control
- **I²C** peripherals + **NEC IR** protocol decoding
- **UART** telemetry + Python live-plot validation framework
- **±3°C** accuracy across 25–240°C

`CV-8052` `FPGA` `I²C` `IR Decode` `UART` `PWM`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📺 FPGA VGA Driver
**Memory-Mapped Display & Game Engine**

- Bare-metal **VGA driver** using MMIO pixel buffer on DE10-Lite
- **RGB565** color packing via bitmask/shift pipeline
- Autonomous robot opponent with **real-time VGA buffer** collision reads

`SystemVerilog` `MMIO` `VGA` `RGB565` `Embedded C`

</td>
<td width="50%" valign="top">

### 📡 Norsat — RF Hardware Test
**Ku-Band BUC/LNB Characterization**

- Characterized **Ku-Band BUCs** using VNA, signal analyzers, oscilloscopes
- Stabilized RF power modules by sweeping **DAC control codes**
- **PCBA-level** SMT/THT soldering & microscopic inspection
- 100% yield across **50+ production BUC units**

`VNA` `RF Systems` `PCB Debug` `SMT` `Schematic Analysis`

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=danielwhn25&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&icon_color=00b4d8&text_color=c9d1d9&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=danielwhn25&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00b4d8&text_color=c9d1d9&langs_count=8"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=danielwhn25&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=00b4d8&ring=00b4d8&fire=ff9d00&currStreakLabel=00b4d8" alt="GitHub Streak" />

</div>

---

## 🏆 Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=danielwhn25&theme=darkhub&no-frame=true&column=7&margin-w=8&title_color=00b4d8)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## 📡 Currently Focused On

```
[ FIRMWARE ]  Bare-metal C on 8051/ESP32 — no HAL, no hand-holding
[ FPGA     ]  SystemVerilog RTL design & simulation on DE10-Lite
[ RF/HW    ]  PCB bring-up, signal integrity, VNA characterization
[ COMMS    ]  CAN, SPI, I²C, UART, ESP-NOW, BLE wireless protocols
[ RTOS     ]  Interrupt-driven architectures and deterministic scheduling
[ NEXT     ]  Diving deeper into STM32, ARM Cortex-M, and custom PCB design
```

---

<div align="center">

<!-- FOOTER WAVE -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0077b6,50:00b4d8,100:0d1117&height=120&section=footer" />

*"The best firmware is the kind that runs forever without a watchdog reset."*

</div>
