<p align="center">
  <img src="./firmware-banner.gif" alt="Nirzor Deb — Embedded Systems and IoT. Animated detailed STM32F407 Discovery board reconstruction. Open to internship and thesis opportunities in Finland." width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nirzor-deb-opi-635846336/"><img src="./linkedin.svg" alt="LinkedIn" width="160" /></a>
  <a href="mailto:nirzordeb79@gmail.com"><img src="./email.svg" alt="Email" width="160" /></a>
  <a href="https://github.com/nirzor-deb-25?tab=repositories"><img src="./repos.svg" alt="Browse repositories" width="160" /></a>
</p>

<p align="center"><strong>STM32 firmware · Bare-metal C · Real-time systems · Embedded ML</strong><br/>
Industrial Information Technology student at LAB University of Applied Sciences, Finland.<br/>
Seeking embedded software internships and thesis opportunities.</p>

<p align="center">
<a href="#about"><img src="./nav-about.gif" alt="About" width="18%" /></a>
<a href="#tech-stack"><img src="./nav-tech-stack.gif" alt="Tech Stack" width="18%" /></a>
<a href="#selected-projects"><img src="./nav-selected-projects.gif" alt="Projects" width="18%" /></a>
<a href="#learning-goals"><img src="./nav-learning-goals.gif" alt="Learning Goals" width="18%" /></a>
<a href="#opportunities"><img src="./nav-opportunities.gif" alt="Contact" width="18%" /></a>
</p>

---

<a name="about"></a>
<h2><img src="./heading-about.gif" alt="About" width="100%" /></h2>

<table>
<tr>
<td width="35%" align="center" valign="middle">
<img src="./portrait-hologram.gif" alt="Animated neon-green holographic portrait of Nirzor, based on his illustrated photo." width="280" /><br/>
<strong>NIRZOR DEB</strong><br/>
<sub>Embedded Systems &amp; IoT · Finland</sub>
</td>
<td width="65%" valign="middle">
<p>I am an engineering student at <strong>LAB University of Applied Sciences, Finland</strong>, focused on <strong>Embedded Systems and IoT</strong>.</p>
<p>I build practical projects with C and STM32 to understand how firmware, hardware, and sensor data work together.</p>
<p>My portfolio covers bare-metal firmware, memory management, bootloaders, FreeRTOS, and Cortex-M4 debugging. My recent projects connect Python model training with embedded C deployment for motion classification and temperature forecasting.</p>
<p><strong>Seeking internship and thesis opportunities in Finland.</strong></p>
</td>
</tr>
</table>

<p align="center"><img src="./about-3d.gif" alt="Animated STM32F407 Discovery board with USB connectors, pin headers, MCU, buttons, and audio jack." width="100%" /></p>

| My focus | Portfolio examples |
| --- | --- |
| Understand the hardware | Direct register access, GPIO, timers, UART, DMA, and SPI sensor interfacing |
| Investigate firmware behavior | GDB/SWD fault investigation, captured exception context, and allocator tests |
| Build toward intelligent devices | Sensor integration, real-time projects, and on-device machine learning |

<a name="tech-stack"></a>
<h2><img src="./heading-tech-stack.gif" alt="Tech Stack" width="100%" /></h2>

<p align="center"><img src="./tech-3d.gif" alt="Animated STM32F407 Discovery board alongside firmware tools and skills." width="100%" /></p>

| Category | Hands-on experience |
| --- | --- |
| **Programming** | C, Embedded C, C++ for Arduino; Python for ML training workflows |
| **Microcontroller** | STM32F407 / ARM Cortex-M4; register-level programming without HAL |
| **Peripherals** | GPIO, interrupts, timers/PWM, UART, DMA, SPI sensor interfacing |
| **Real-time firmware** | FreeRTOS projects, producer-consumer patterns, cooperative scheduling |
| **Boot & build** | UART firmware updates, bootloader projects, Makefiles, arm-none-eabi-gcc |
| **Debugging** | ST-LINK, SWD, GDB, Cortex-M4 HardFault investigation |
| **Memory management** | Pool/heap allocators, splitting/coalescing, corruption detection, testing |
| **Embedded ML** | Motion classification, ridge-regression forecasting, on-device verification |
| **Development tools** | STM32CubeIDE, Git, GitHub, Wokwi |

<details>
<summary><strong>Hardware available for further projects</strong></summary>

- STM32F407G-DISC1 and NUCLEO-F439ZI.
- ESP32 development boards and Arduino Uno.
- Raspberry Pi 3B+ and Olimex MOD-BME280 sensor module.

</details>

<a name="selected-projects"></a>
<h2><img src="./heading-selected-projects.gif" alt="Selected Projects" width="100%" /></h2>

| Project | Focus | What to explore |
| --- | --- | --- |
| [STM32 MotionSense](https://github.com/nirzor-deb-25/stm32-motionsense) | Bare-metal firmware & embedded ML | Motion classification on STM32, Python training, and deployment verification. |
| [STM32 ThermalPredict](https://github.com/nirzor-deb-25/stm32-thermalpredict) | Sensor data & forecasting | BME280 temperature measurements, ridge regression, and on-device verification. |
| [Memory Allocators in C](https://github.com/nirzor-deb-25/embedded-c-memory-allocator-) | Memory management | Fixed-size pools, heap splitting/coalescing, and a hardened allocator with tests and benchmarks. |
| [STM32 HardFault Debugging](https://github.com/nirzor-deb-25/stm32_hardfault_debug) | Cortex-M4 debugging | GDB/SWD investigation, captured exception context, and a verified alignment-safe fix. |
| [STM32 FreeRTOS Sensor System](https://github.com/nirzor-deb-25/stm32_freertos_sensor_system) | Real-time firmware | A sensor-system project exploring FreeRTOS on STM32. |
| [STM32 Multi-Protocol Sensor Hub](https://github.com/nirzor-deb-25/stm32_multiprotocol_sensor_hub) | Sensor interfaces | A sensor-hub project exploring multiple communication interfaces on STM32. |

<details>

<summary><strong>Explore the rest of my firmware projects</strong></summary>

**Drivers, scheduling & firmware updates**

- [SPI LIS3DSH Sensor Interface](https://github.com/nirzor-deb-25/stm32_spi_lis3dsh)
- [FreeRTOS Producer-Consumer](https://github.com/nirzor-deb-25/stm32_freertos_producer_consumer)
- [Cooperative Scheduler](https://github.com/nirzor-deb-25/stm32_cooperative_scheduler)
- [Ground-Up Bootloader](https://github.com/nirzor-deb-25/stm32_groundup_bootloader)
- [UART Bootloader](https://github.com/nirzor-deb-25/stm32_uart_bootloader)

**Bare-metal foundations**

- [Register-Level LED & Button Control](https://github.com/nirzor-deb-25/stm32_register_led_button) — debouncing, single/double clicks, and long-press detection without HAL.
- [Makefile-Based STM32 Project](https://github.com/nirzor-deb-25/stm32_makefile_project) — incremental builds and command-line flashing.
- [DMA UART Echo](https://github.com/nirzor-deb-25/stm32_dma_uart_echo)
- [PWM LED Dimmer](https://github.com/nirzor-deb-25/stm32_pwm_led_dimmer)
- [Smart LED Controller](https://github.com/nirzor-deb-25/stm32_smart_led_controller)
- [STM32 Learning Collection](https://github.com/nirzor-deb-25/stm32-basic-learning) — 11 projects covering C, GPIO, interrupts, volatile, structure packing, bitfields, and keypad input.

**Arduino & IoT**

- [Arduino Projects](https://github.com/nirzor-deb-25/Arduino-Projects-) — Wokwi projects covering sensors, motors, displays, and embedded fundamentals.
- [NFC-Based Attendance System](https://github.com/nirzor-deb-25/NFC-BASED-ATTENDANCE-SYSTEM)

</details>

<a name="learning-goals"></a>
<h2><img src="./heading-learning-goals.gif" alt="Learning Goals" width="100%" /></h2>

These are the next areas I want to develop through practical projects.

| Direction | Next project goal |
| --- | --- |
| **Connected devices** | Publish ESP32 sensor measurements over MQTT |
| **Visualization & control** | Create a Node-RED dashboard for remote device control |
| **Embedded Linux** | Cross-compile C applications and explore Raspberry Pi GPIO |
| **Data quality** | Build a room digital twin with sensor noise handling and quality checks |

<a name="opportunities"></a>
<h2><img src="./heading-opportunities.gif" alt="Opportunities" width="100%" /></h2>

I am seeking an **embedded software / embedded systems internship or thesis opportunity in Finland**. My interests include embedded C, STM32 firmware, sensor integration, real-time systems, and IoT.

If your team is working in these areas, I would be happy to discuss how I can contribute and learn.

<p align="center">
  <a href="mailto:nirzordeb79@gmail.com"><img src="./email.svg" alt="Email Nirzor" width="160" /></a>
  <a href="https://www.linkedin.com/in/nirzor-deb-opi-635846336/"><img src="./linkedin.svg" alt="Connect on LinkedIn" width="160" /></a>
</p>

<p align="center"><a href="mailto:nirzordeb79@gmail.com">nirzordeb79@gmail.com</a><br/><sub>Build. Debug. Understand.</sub></p>

<details>
<summary>Visual credits</summary>

Board animation: a custom 3D reconstruction based on the STM32F407G-DISC1 layout in [STMicroelectronics UM1472](https://www.st.com/resource/en/user_manual/um1472-stm32f4-discovery-stmicroelectronics.pdf). Component placement and geometry are simplified for this portfolio; this is not a manufacturing model.

</details>
