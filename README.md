# Nirzor Deb

**Embedded Systems & IoT** | Industrial Information Technology student at LAB University of Applied Sciences, Finland

Open to internship and thesis opportunities in embedded systems and IoT in Finland.

[LinkedIn](https://www.linkedin.com/in/nirzor-deb-opi-635846336) | [Email](mailto:nirzordeb79@gmail.com)

---

## About

I write firmware from the register level up. My work so far covers bare-metal STM32 programming (GPIO, timers/PWM, UART, DMA), a bootloader that updates firmware over UART, and a custom memory allocator in C. Every concept I study becomes a hands-on project that I document and publish here. I am now moving on to drivers, RTOS and IoT connectivity.

---

## Technical Skills

**Hands-on experience**

- **Languages:** C, Embedded C, C++ (Arduino)
- **Microcontroller:** STM32F407 (ARM Cortex-M4), register-level programming without HAL
- **Peripherals:** GPIO, timers/PWM, UART, DMA
- **Firmware:** custom bootloader (firmware update over UART), Makefile-based builds with command-line flashing
- **Memory management:** custom allocators with corruption detection (buffer overrun, double free, invalid free)
- **Tools:** STM32CubeIDE, ST-LINK (SWD) debugging, arm-none-eabi-gcc, Git and GitHub, Wokwi

**Currently learning**

- FreeRTOS (tasks, queues, semaphores)
- I2C and SPI driver development
- ESP32, MQTT and Node-RED
- Ethernet and embedded Linux basics

---

## Featured Projects

**[Memory Allocator in C](https://github.com/nirzor-deb-25/embedded-c-memory-allocator-)**
Three versions of increasing sophistication: a fixed-size pool, a general-purpose heap with block splitting and coalescing, and a hardened version with calloc, realloc, aligned allocation, thread safety and corruption detection. Includes a test suite, a benchmark against the system allocator, and demos that trigger memory bugs on purpose.

**[STM32 Register-Level LED and Button](https://github.com/nirzor-deb-25/stm32_register_led_button)**
LED patterns on the STM32F407 using direct register access, with no HAL. Button debouncing, single and double click detection, and long-press detection.

**[STM32 Makefile Project](https://github.com/nirzor-deb-25/stm32_makefile_project)**
Multi-file STM32 C project with a handwritten Makefile, incremental builds and command-line flashing.

---

## Project Roadmap

7 of 18 projects completed. Next: custom I2C/SPI driver, then a multi-task FreeRTOS sensor system.

<details>
<summary><b>Show the full project roadmap</b></summary>

| # | Phase | Project | Status |
|---|---|---|---|
| 1 | Foundation | Custom memory allocator in C | Completed |
| 2 | Foundation | LED blink and button patterns on STM32, register-level, no HAL | Completed |
| 3 | Foundation | Makefile-based build system for a multi-file STM32 project | Completed |
| 4 | MCU peripherals | PWM-based LED dimmer / motor speed control | Completed |
| 5 | MCU peripherals | DMA-based UART echo (no CPU polling) | Completed |
| 6 | MCU peripherals | Custom bootloader: firmware update over UART | Completed |
| 7 | MCU peripherals | Smart LED controller: button input, PWM brightness, bootloader-flashable firmware | Completed |
| 8 | Drivers and debugging | Custom I2C or SPI driver from scratch, no HAL | Planned |
| 9 | Drivers and debugging | Debug and document a deliberately broken firmware (hard fault, GDB/SWD) | Planned |
| 10 | Drivers and debugging | Full ground-up bootloader | Planned |
| 11 | RTOS | Multi-task FreeRTOS system: I2C sensor task, LED task, UART command task (flagship) | Planned |
| 12 | RTOS | Producer-consumer pattern with FreeRTOS queues | Planned |
| 13 | RTOS | Minimal cooperative scheduler built from scratch | Planned |
| 14 | Protocols and wireless | Multi-protocol sensor hub: I2C sensor, SPI device, UART reporting | Planned |
| 15 | Protocols and wireless | ESP32 IoT temperature logger publishing to MQTT (flagship) | Planned |
| 16 | Protocols and wireless | WiFi-enabled remote LED/relay control with a Node-RED dashboard (flagship) | Planned |
| 17 | Embedded Linux | Cross-compile a C application for a Raspberry Pi / embedded Linux target | Planned |
| 18 | Embedded Linux | GPIO control from Linux userspace on Raspberry Pi | Planned |

</details>

<details>
<summary><b>Show the learning path</b></summary>

Self-directed, using online courses alongside the projects above.

- **Foundation:** C programming in depth, embedded C fundamentals
- **MCU peripherals:** bare-metal STM32 programming, timers/PWM/CAN/low power, DMA, custom bootloader development
- **Drivers and debugging:** ARM Cortex-M architecture, embedded driver development, bootloader from the ground up
- **RTOS:** FreeRTOS on STM32 and ARM processors
- **Protocols and wireless:** UART/I2C/SPI, Ethernet with HAL, WiFi, MQTT, ESP32, Node-RED
- **Embedded Linux (partial):** fundamentals and cross-compilation

</details>

---

## Contact

- Email: [nirzordeb79@gmail.com](mailto:nirzordeb79@gmail.com)
- LinkedIn: [linkedin.com/in/nirzor-deb-opi-635846336](https://www.linkedin.com/in/nirzor-deb-opi-635846336)
