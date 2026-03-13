<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,40:003049,100:023e8a&height=220&section=header&text=Daniel%20Ng&fontSize=72&fontColor=90e0ef&fontAlignY=35&desc=Electrical%20Engineering%20Student%20%7C%20Embedded%20Systems%20%7C%20Firmware&descAlignY=70&descSize=19&animation=fadeIn" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=18&duration=3000&pause=800&color=90E0EF&center=true&vCenter=true&width=750&lines=Bare-metal+firmware+on+ARM+Cortex+%2B+8051+%2B+RISC-V;RF+%26+hardware+test+%40+Norsat+(Ku-Band+BUCs%2FLNBs);Timing+Gates+Project+Lead+%40FormulaUBC;STM32+%7C+ESP32+%7C+EFM8+%7C+I%C2%B2C+%7C+SPI+%7C+CAN+%7C+RS-485" />
</a>

<br/><br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/danielngEE)
[![Portfolio](https://img.shields.io/badge/Portfolio-023e8a?style=flat-square&logo=vercel&logoColor=white)](https://danielng.pages.dev)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:daniel.whn@outlook.com)
![Views](https://komarev.com/ghpvc/?username=danielwhn25&color=023e8a&style=flat-square&label=Profile+Views)

</div>

---

## About Me

```c
/* daniel_ng.h  —  last compiled: 2026 */

#ifndef DANIEL_NG_H
#define DANIEL_NG_H

#define SCHOOL    "UBC Electrical Engineering (BASc Co-op · May 2028)"
#define AVAILABLE "May 2026 — co-op / internship"
#define PREV      "Hardware Test Intern @ Norsat (Ku-Band RF systems)"
#define NOW       "Timing Gates Project Lead @ FormulaUBC"

typedef struct {
    char  *mcus[]    = { "STM32L051", "ESP32-S3", "EFM8", "N76E003",
                         "CV-8052", "RISC-V" };
    char  *protos[]  = { "I2C", "SPI", "UART", "CAN", "USB",
                         "RS-485", "NEC IR", "ESP-NOW" };
    char  *hdl[]     = { "A51 Assembly", "RISC-V ASM" };
    char  *tools[]   = { "Altium Designer", "VNA", "Signal Analyzer", 
                         "Oscilloscope" };
    bool   open_to   = INTERNSHIPS | COLLAB | OPEN_SOURCE;
} Engineer_t;

#endif
```

---

## Hardware & Firmware Stack

<div align="center">

**Microcontrollers & Processors**

![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32--S3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![ARM Cortex](https://img.shields.io/badge/ARM%20Cortex-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![8051](https://img.shields.io/badge/8051%20%2F%20EFM8-444444?style=for-the-badge&logoColor=white)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=for-the-badge&logo=riscv&logoColor=white)

**Languages & Low-Level**

![C](https://img.shields.io/badge/Embedded%20C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-004482?style=for-the-badge&logo=cplusplus&logoColor=white)
![Assembly](https://img.shields.io/badge/A51%20Assembly-6E4C13?style=for-the-badge&logoColor=white)
![RISC-V ASM](https://img.shields.io/badge/RISC--V%20ASM-283272?style=for-the-badge&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Makefile](https://img.shields.io/badge/Makefile-427819?style=for-the-badge&logoColor=white)

**Communication Protocols**

![I2C](https://img.shields.io/badge/I%C2%B2C-222222?style=for-the-badge)
![SPI](https://img.shields.io/badge/SPI-222222?style=for-the-badge)
![UART](https://img.shields.io/badge/UART-222222?style=for-the-badge)
![CAN](https://img.shields.io/badge/CAN%20Bus-FF6600?style=for-the-badge)
![RS485](https://img.shields.io/badge/RS--485-555555?style=for-the-badge)
![USB](https://img.shields.io/badge/USB-5C2D91?style=for-the-badge&logo=usb&logoColor=white)
![ESP-NOW](https://img.shields.io/badge/ESP--NOW-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![NEC IR](https://img.shields.io/badge/NEC%20IR-333333?style=for-the-badge)

**PCB & Lab Equipment**

![Altium](https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white)
![VNA](https://img.shields.io/badge/Vector%20Network%20Analyzer-8B0000?style=for-the-badge)
![Scope](https://img.shields.io/badge/Oscilloscope-1A1A2E?style=for-the-badge)
![RF Analyzer](https://img.shields.io/badge/RF%20Signal%20Analyzer-006400?style=for-the-badge)
![Soldering](https://img.shields.io/badge/SMT%2FTHT%20Soldering-5C4033?style=for-the-badge)

</div>

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### Digital Multimeter — STM32L051
`Makefiles` `Embedded C` `STM32` `ADC` `Timers`

Full bare-metal RLC meter on an STM32L051:
- Calibrated **ADC sampling** for resistance/voltage
- **Timer-based frequency capture** via astable 555 circuit
- **CMOS inverter-based inductance** measurement
- Modular LCD/ADC/serial **driver architecture** with Makefile build system
- Event-driven **IR remote + button** HMI; instant continuity detection

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/danielwhn25/ELEC291_labs/tree/main/DMM_STM32LO51)

</td>
<td width="50%" valign="top">

### UBC Formula Racing — Laser Lap Timer
`ESP32-S3` `ESP-NOW` `Analog Front End` `Wireless`

End-to-end laser speed & lap timing system:
- Custom **3.3V CMOS analog front end** with optomechanical shrouding
- **Master/slave ESP32-S3** MCUs over 2.4 GHz ESP-NOW
- TIA noise + dark current characterization → adjustable hysteresis
- Target: **20 dB SNR**, **BER < 10⁻⁷**

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/danielwhn25/FUBC-timing-gates)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Oven Reflow Controller — 8052 Bare Metal
`A51 Assembly` `8052 uC` `NEC IR` `I2C` `PWM`

Deterministic thermal FSM on the 8052 uC:
- **PWM closed-loop** control with ADC sensor feedback
- **Bit-level NEC IR** decoding + LCD/7-seg HMI
- **UART telemetry** + Python live-plot validation
- **±3°C accuracy** across 25–240°C thermal profile

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/danielwhn25/4C11IV)

</td>
<td width="50%" valign="top">
</td>
</tr>
</table>

---

## GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=danielwhn25&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=90e0ef&icon_color=90e0ef&text_color=c9d1d9&include_all_commits=true&count_private=true"/>
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=danielwhn25&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=90e0ef&text_color=c9d1d9&langs_count=8"/>

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=danielwhn25&theme=github-dark-blue&hide_border=true&background=0d1117&ring=90e0ef&fire=ff9d00&currStreakLabel=90e0ef" />

</div>

---

## Personal "OSI Layer"

```text
 LAYER 0  |  A51 / RISC-V Assembly — hand-crafted ISR tables
 LAYER 1  |  Bare-metal C drivers — no HAL, no RTOS hand-holding
 LAYER 2  |  Protocol stacks — I2C, SPI, CAN, RS-485 from scratch
 LAYER 3  |  Analog front ends — TIA, ADC, noise characterization
 LAYER 4  |  RF & PCB — signal integrity, VNA, schematic debug
 NEXT UP  |  FreeRTOS on ARM Cortex-M, custom Altium PCB bring-up
```

---

<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:023e8a,60:003049,100:0d1117&height=120&section=footer" />

*`while(alive) { learn(); build(); debug(); }`*

</div>
