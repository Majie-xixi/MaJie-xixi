<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=900&center=true&vCenter=true&width=920&lines=Embedded+software+developer;MCU+firmware+%7C+Embedded+Linux+%7C+RTOS;Caffeine+loaded%2C+debugger+attached%2C+serial+console+alive" alt="Typing intro">

# Majie

**MCU firmware · Embedded Linux · Board bring-up · RTOS tooling**

<img src="assets/embedded-linux-lab.png" alt="Embedded Linux board bring-up and IRQ debug lab" width="100%">

</div>

## About

I work close to the hardware: **MCU firmware**, **embedded Linux**, **ARM boards**, **RTOS integration**, serial debugging, build systems, and small tools that make bring-up less painful.

I like the part where software meets real signals: GPIO, UART logs, startup files, linker scripts, interrupt paths, SDK layouts, and board-specific details that decide whether a project boots cleanly.

**Reach me at:** [mjie51939@gmail.com](mailto:mjie51939@gmail.com)

## Technologies

<div align="center">

[![C](https://img.shields.io/badge/C-111827?style=for-the-badge&logo=c&logoColor=5EEAD4)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Linux](https://img.shields.io/badge/Linux-111827?style=for-the-badge&logo=linux&logoColor=FACC15)](https://www.kernel.org/)
[![ARM](https://img.shields.io/badge/ARM_Cortex--M-111827?style=for-the-badge&logo=arm&logoColor=60A5FA)](https://www.arm.com/)
[![STM32](https://img.shields.io/badge/STM32-111827?style=for-the-badge&logo=stmicroelectronics&logoColor=60A5FA)](https://www.st.com/)
[![GD32](https://img.shields.io/badge/GD32-111827?style=for-the-badge&logoColor=5EEAD4)](https://www.gigadevice.com/)
[![FreeRTOS](https://img.shields.io/badge/FreeRTOS-111827?style=for-the-badge&logoColor=A7F3D0)](https://www.freertos.org/)
[![RT-Thread](https://img.shields.io/badge/RT--Thread-111827?style=for-the-badge&logoColor=93C5FD)](https://www.rt-thread.io/)
[![CMake](https://img.shields.io/badge/CMake-111827?style=for-the-badge&logo=cmake&logoColor=5EEAD4)](https://cmake.org/)
[![Python](https://img.shields.io/badge/Python-111827?style=for-the-badge&logo=python&logoColor=FACC15)](https://www.python.org/)
[![Qt](https://img.shields.io/badge/PyQt6-111827?style=for-the-badge&logo=qt&logoColor=41CD52)](https://www.qt.io/)

</div>

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

## Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Majie-xixi&show_icons=true&theme=github_dark&hide_border=true&rank_icon=github&include_all_commits=true" alt="GitHub stats">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Majie-xixi&layout=compact&theme=github_dark&hide_border=true&langs_count=8" alt="Top languages">

<img width="720" src="https://streak-stats.demolab.com?user=Majie-xixi&theme=github-dark-blue&hide_border=true" alt="GitHub streak">

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=Majie-xixi&theme=github-compact&hide_border=true&area=true&custom_title=Contribution%20Activity" alt="Contribution activity graph">

</div>

## Current Work

Mostly embedded tooling and project setup experiments. One small example is [MCUQuickStart](https://github.com/Majie-xixi/MCUQuickStart), a STM32/GD32 project generator.

## Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="snake/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="snake/github-contribution-grid-snake.svg">
  <img alt="GitHub contribution snake" src="snake/github-contribution-grid-snake.svg">
</picture>
