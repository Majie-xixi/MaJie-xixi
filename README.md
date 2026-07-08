<div align="center">

# Majie

**Embedded software developer focused on MCU and embedded Linux**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![ARM](https://img.shields.io/badge/ARM_Cortex--M-0091BD?style=for-the-badge&logo=arm&logoColor=white)
![STM32](https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white)
![GD32](https://img.shields.io/badge/GD32-GigaDevice-00A4EF?style=for-the-badge)
![FreeRTOS](https://img.shields.io/badge/FreeRTOS-3A3A3A?style=for-the-badge)
![RT-Thread](https://img.shields.io/badge/RT--Thread-0A66C2?style=for-the-badge)

<img src="assets/terminal-motto.svg" alt="Embedded developer terminal motto" width="100%">

<img src="assets/embedded-linux-lab.png" alt="Embedded Linux board bring-up and IRQ debug lab" width="100%">

</div>

## About

I work close to the hardware: **MCU firmware**, **embedded Linux**, **ARM boards**, **RTOS integration**, serial debugging, build systems, and the small tools that make bring-up less painful.

I like the part where software meets real signals: GPIO, UART logs, startup files, linker scripts, interrupt paths, SDK layouts, and board-specific details that decide whether a project boots cleanly.

**Reach me at:** [mjie51939@gmail.com](mailto:mjie51939@gmail.com)

## Focus

| Area | What I care about |
| --- | --- |
| Embedded Linux | board bring-up, serial console, GPIO / IRQ debug, driver-facing workflows |
| MCU firmware | STM32 / GD32, ARM Cortex-M, startup code, linker scripts, peripheral templates |
| RTOS work | FreeRTOS, RT-Thread Nano, SysTick and delay adaptation |
| Tooling | C, Python, PyQt6, Keil MDK, GCC, CMake, project scaffolding |

## Lab Notes

```text
$ dmesg | grep -i "gpio\|irq\|uart"
[    0.421] arm64 board online
[    1.037] ttyS0: serial console attached
[    1.284] gpiochip0: registered 96 lines
[    1.619] irq/42-gpio: edge interrupt ready
[    2.006] userland: caffeine loaded, debugger attached
```

## Working Range

| Layer | Tools / Topics |
| --- | --- |
| Board | ARM SBCs, MCU dev boards, UART adapters, GPIO headers |
| Kernel-facing | interrupts, serial logs, device bring-up, debug traces |
| Firmware | startup files, linker scripts, peripheral init, RTOS timing |
| Application tools | Python utilities, PyQt6 desktop tools, project generators |

## Current Work

Mostly embedded tooling and project setup experiments. One small example is [MCUQuickStart](https://github.com/Majie-xixi/MCUQuickStart), a STM32/GD32 project generator.

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="snake/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="snake/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution snake" src="snake/github-contribution-grid-snake.svg">
</picture>
