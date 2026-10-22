<p align="center">
  <img src="./assets/firmware-banner.gif" alt="Nirzor Deb — Embedded Systems and IoT. Animated rotating STM32-style chip. Open to internship and thesis opportunities in Finland." width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nirzor-deb-opi-635846336/"><img src="./assets/linkedin.svg" alt="LinkedIn" width="160" /></a>
  <a href="mailto:nirzordeb79@gmail.com"><img src="./assets/email.svg" alt="Email" width="160" /></a>
  <a href="https://github.com/nirzor-deb-25?tab=repositories"><img src="./assets/repos.svg" alt="Browse repositories" width="160" /></a>
</p>

<p align="center"><strong>STM32 firmware · Bare-metal C · Real-time systems · Embedded ML</strong><br/>
Industrial Information Technology student at LAB University of Applied Sciences, Finland.<br/>
Seeking embedded software internships and thesis opportunities.</p>

---

### `01 / ABOUT`

I build firmware to understand what happens between the code and the hardware. My work spans register-level STM32 programming, memory allocators, UART bootloaders, Cortex-M4 fault investigation, and FreeRTOS projects.

My recent projects explore **motion classification and temperature forecasting on STM32**, connecting Python model training with embedded C deployment and on-device verification.

```c
/* My approach to learning embedded systems */
while (learning) {
    build();
    measure();
    debug();
    document();
}
```

### `02 / SELECTED PROJECTS`

| Project | Focus | What to explore |
| --- | --- | --- |
| [STM32 MotionSense](https://github.com/nirzor-deb-25/stm32-motionsense) | Bare-metal firmware & embedded ML | Motion classification on STM32, Python training, and deployment verification. |
| [STM32 ThermalPredict](https://github.com/nirzor-deb-25/stm32-thermalpredict) | Sensor data & forecasting | BME280 temperature measurements, ridge regression, and on-device verification. |
| [Memory Allocators in C](https://github.com/nirzor-deb-25/embedded-c-memory-allocator-) | Memory management | Fixed-size pools, heap splitting/coalescing, and a hardened allocator with tests and benchmarks. |
| [STM32 HardFault Debugging](https://github.com/nirzor-deb-25/stm32_hardfault_debug) | Cortex-M4 debugging | GDB/SWD investigation, captured exception context, and a verified alignment-safe fix. |
| [STM32 FreeRTOS Sensor System](https://github.com/nirzor-deb-25/stm32_freertos_sensor_system) | Real-time firmware | My STM32 sensor-system project using FreeRTOS. |
| [STM32 Multi-Protocol Sensor Hub](https://github.com/nirzor-deb-25/stm32_multiprotocol_sensor_hub) | Sensor interfaces | My STM32 project focused on a sensor hub using multiple communication protocols. |

### `03 / TECH STACK`

| Area | Hands-on work |
| --- | --- |
| Languages | C, Embedded C, C++ for Arduino; Python for embedded ML training workflows |
| Microcontroller | STM32F407, ARM Cortex-M4, register-level programming without HAL |
| Peripherals & interfaces | GPIO, interrupts, timers/PWM, UART, DMA; SPI sensor interfacing and multi-protocol projects |
| Real-time systems | FreeRTOS projects, producer-consumer patterns, cooperative scheduling |
| Firmware & builds | UART firmware updates, bootloader projects, multi-file C projects, handwritten Makefiles |
| Debugging | ST-LINK/SWD, GDB, Cortex-M4 HardFault investigation |
| Memory management | Pool and heap allocators, split/coalesce, corruption detection, allocator testing |
| Embedded ML | Motion classification, ridge-regression temperature forecasting, on-device verification |
| Tools | STM32CubeIDE, arm-none-eabi-gcc, Git, GitHub, Wokwi |

<details>
<summary><strong>04 / More firmware projects — expand</strong></summary>

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

### `05 / NEXT ON MY BENCH`

- ESP32 sensor logging over MQTT.
- Node-RED device control and visualization.
- Ethernet connectivity and Raspberry Pi embedded Linux.
- A room digital twin focused on sensor data quality and noise handling.

---

<p align="center"><strong>Let's build reliable embedded systems.</strong><br/>
<a href="mailto:nirzordeb79@gmail.com">nirzordeb79@gmail.com</a> · <a href="https://www.linkedin.com/in/nirzor-deb-opi-635846336/">LinkedIn</a></p>
