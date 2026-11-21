<p align="center">
  <img src="./stm32-discovery-hero-v5.gif" alt="Nirzor Deb — Embedded Systems and IoT. Realistic 3D-rendered STM32F407 Discovery board animation. Open to internship and thesis opportunities in Finland." width="100%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/nirzor-deb-opi-635846336/"><img src="./linkedin-3d.svg" alt="LinkedIn" width="160" /></a>
  <a href="mailto:nirzordeb79@gmail.com"><img src="./email-3d.svg" alt="Email" width="160" /></a>
  <a href="https://github.com/nirzor-deb-25?tab=repositories"><img src="./repos-3d.svg" alt="Browse repositories" width="160" /></a>
</p>

<p align="center"><strong>Embedded C · STM32 Firmware · ARM Cortex-M · FreeRTOS · IoT · Embedded ML</strong><br/>
Industrial Information Technology student at LAB University of Applied Sciences, Finland.<br/>
Open to embedded software internships and industry-connected thesis opportunities in Finland.</p>

<p align="center">
<a href="#about"><img src="./nav-about.gif" alt="About" width="18%" /></a>
<a href="#tech-stack"><img src="./nav-tech-stack.gif" alt="Tech Stack" width="18%" /></a>
<a href="#selected-projects"><img src="./nav-selected-projects.gif" alt="Projects" width="18%" /></a>
<a href="#learning-goals"><img src="./nav-learning-goals.gif" alt="Learning Goals" width="18%" /></a>
<a href="#opportunities"><img src="./nav-opportunities.gif" alt="Contact" width="18%" /></a>
</p>

<p align="center"><a href="#certificates-and-training"><img src="./heading-certificates.gif" alt="Certificates and Training" width="42%" /></a></p>

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
<p>My focus is on <strong>low-level embedded software</strong>: programming microcontrollers, working with hardware peripherals, and understanding how systems behave under real-world constraints.</p>
<p>My selected projects span <strong>register-level STM32 development, DMA, firmware bootloaders, Cortex-M4 fault debugging, FreeRTOS, sensor interfaces, IoT prototypes, and embedded machine learning</strong>. I am strengthening my ability to independently explain, test, and debug the engineering decisions behind each implementation.</p>
<p><strong>Seeking internship and thesis opportunities in Finland.</strong></p>
</td>
</tr>
</table>

<p align="center"><img src="./stm32-discovery-about-v5.gif" alt="Animated STM32F407 Discovery board with USB connectors, pin headers, MCU, buttons, and audio jack." width="100%" /></p>

| My focus | Portfolio examples |
| --- | --- |
| Understand the hardware | Direct register access, GPIO, timers, UART, DMA, and SPI sensor interfacing |
| Investigate firmware behavior | GDB/SWD fault investigation, captured exception context, and allocator tests |
| Develop connected and intelligent devices | NFC attendance, TwinTrust sensor-data validation, and STM32 machine-learning experiments |

<a name="tech-stack"></a>
<h2><img src="./heading-tech-stack.gif" alt="Tech Stack" width="100%" /></h2>

<p align="center"><img src="./stm32-discovery-tech-v5.gif" alt="Animated STM32F407 Discovery board alongside firmware tools and skills." width="100%" /></p>

| Category | Hands-on experience |
| --- | --- |
| **Programming** | C, Embedded C, C++ for Arduino; Python for ML training workflows |
| **Microcontroller** | STM32F407 / ARM Cortex-M4; register-level programming without HAL |
| **Peripherals** | GPIO, interrupts, timers/PWM, UART, DMA, SPI sensor interfacing |
| **Real-time firmware** | FreeRTOS sensor tasks, queues and scheduling concepts |
| **Boot & build** | UART firmware updates, bootloader projects, Makefiles, arm-none-eabi-gcc |
| **Debugging** | ST-LINK, SWD, GDB, Cortex-M4 HardFault investigation |
| **Memory management** | Pool/heap allocators, splitting/coalescing, corruption detection, testing |
| **Embedded ML & modeling** | Motion classification, anomaly detection, regression-based prediction, and power-system simulation projects |
| **Development tools** | STM32CubeIDE, GCC/Make, Git, GitHub, GDB, ST-LINK, Wokwi |

<details>
<summary><strong>Hardware available for further projects</strong></summary>

- STM32F407G-DISC1 and NUCLEO-F439ZI.
- ESP32 development boards and Arduino Uno.
- Raspberry Pi 3B+ and Olimex MOD-BME280 sensor module.

</details>

<a name="selected-projects"></a>
<h2><img src="./heading-selected-projects.gif" alt="Selected Projects" width="100%" /></h2>

A curated collection of **16 engineering projects**. The project names below are clickable 3D-style buttons that open the repositories directly.

### Low-Level C & STM32 Fundamentals

<table>
<tr><th align="left">Project</th><th align="left">Engineering focus</th></tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/embedded-c-memory-allocator-"><img src="./btn-memory-allocator.svg" alt="Custom Memory Allocator in C" width="320" /></a></td>
<td>Memory pools, heap allocation, splitting/coalescing, and defensive memory management.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_register_led_button"><img src="./btn-register-led-button.svg" alt="Register-Level LED and Button Control" width="320" /></a></td>
<td>STM32 GPIO/RCC register configuration, button debouncing, and event handling without HAL.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_pwm_led_dimmer"><img src="./btn-pwm-led-dimmer.svg" alt="PWM LED Dimmer" width="320" /></a></td>
<td>Hardware timers, prescalers, PWM output, and duty-cycle control.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_dma_uart_echo"><img src="./btn-dma-uart-echo.svg" alt="DMA UART Echo" width="320" /></a></td>
<td>UART data transfers using DMA, buffer handling, and interrupt-driven firmware concepts.</td>
</tr>
</table>

### Firmware Architecture, Drivers & Debugging

<table>
<tr><th align="left">Project</th><th align="left">Engineering focus</th></tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_uart_bootloader"><img src="./btn-uart-bootloader.svg" alt="UART Firmware Bootloader" width="320" /></a></td>
<td>Firmware loading over UART, flash programming, memory maps, and application startup.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_spi_lis3dsh"><img src="./btn-spi-lis3dsh.svg" alt="SPI LIS3DSH Sensor Driver" width="320" /></a></td>
<td>STM32 SPI peripheral communication and accelerometer register access.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_hardfault_debug"><img src="./btn-hardfault-debug.svg" alt="Cortex-M4 HardFault Debugging" width="320" /></a></td>
<td>Exception-context investigation, GDB/SWD debugging, and a documented alignment-safe fix.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32_freertos_sensor_system"><img src="./btn-freertos-sensor-system.svg" alt="FreeRTOS Sensor System" width="320" /></a></td>
<td>Sensor acquisition, real-time task organization, and FreeRTOS scheduling.</td>
</tr>
</table>

### Connected Devices & IoT

<table>
<tr><th align="left">Project</th><th align="left">Engineering focus</th></tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/Arduino-Projects-"><img src="./btn-arduino-projects.svg" alt="Arduino Projects — Wokwi Simulations" width="320" /></a></td>
<td>Simulated circuits and microcontroller exercises using sensors, motors, and displays.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/NFC-BASED-ATTENDANCE-SYSTEM"><img src="./btn-nfc-attendance.svg" alt="NFC-Based Attendance System" width="320" /></a></td>
<td>NFC-based student identification and attendance-recording system design.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/twintrust-project"><img src="./btn-twintrust.svg" alt="TwinTrust — Sensor Data Quality" width="320" /></a></td>
<td>Sensor-data quality checks and monitoring workflows for more trustworthy readings.</td>
</tr>
</table>

### Embedded Machine Learning & Intelligent Power Systems

<table>
<tr><th align="left">Project</th><th align="left">Engineering focus</th></tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32-motionsense"><img src="./btn-motionsense.svg" alt="STM32 MotionSense" width="320" /></a></td>
<td>Motion classification with STM32 firmware, Python-based training, and deployment verification.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32-machineguard-lite"><img src="./btn-machineguard-lite.svg" alt="STM32 MachineGuard Lite" width="320" /></a></td>
<td>Sensor/vibration anomaly-detection prototype on STM32.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/stm32-thermalpredict"><img src="./btn-thermalpredict.svg" alt="STM32 ThermalPredict" width="320" /></a></td>
<td>BME280 temperature measurements, ridge-regression forecasting, and embedded verification.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/BoostConverterML"><img src="./btn-boostconverterml.svg" alt="BoostConverterML" width="320" /></a></td>
<td>Simulated boost-converter data and machine-learning-assisted estimation experiments.</td>
</tr>
<tr>
<td><a href="https://github.com/nirzor-deb-25/STM32-EV-Climbing-Power-ML"><img src="./btn-ev-climbing-power-ml.svg" alt="STM32 EV Climbing Power ML" width="320" /></a></td>
<td>Electric-vehicle climbing-power estimation using modeled conditions and synthetic acceleration inputs.</td>
</tr>
</table>

> **Engineering approach:** I use development tools, documentation, and AI-assisted guidance where helpful, then work toward validating behavior, understanding the code, and rebuilding important features independently. Hardware tests, simulations, and model-based results should be interpreted according to the evidence in each repository.

<a name="certificates-and-training"></a>
<h2><img src="./heading-certificates.gif" alt="Certificates &amp; Training" width="100%" /></h2>

Completed courses supporting my practical work in embedded C and embedded systems.

| Course | Provider | Completed | Certificate |
| --- | --- | --- | --- |
| **Microcontroller Embedded C Programming: Absolute Beginners** | Udemy · FastBit Embedded Brain Academy / Kiran Nayak | 23 October 2026 · 16.5 hours | [View credential](https://www.udemy.com/certificate/UC-1978d36f-352e-4168-b795-cf2526598547/) · [PDF](./udemy-embedded-c.pdf) |
| **Free Embedded Systems Course** | Simplilearn SkillUp | 23 October 2026 | [PDF](./simplilearn-embedded-systems.pdf) · Certificate code: 10930187 |

<details open>
<summary><strong>Preview my certificates</strong></summary>

### Microcontroller Embedded C Programming: Absolute Beginners

<a href="./udemy-embedded-c.pdf"><img src="./udemy-embedded-c.jpg" alt="Udemy Embedded C course completion certificate awarded to Nirzor Deb Opi on 23 October 2026." width="100%" /></a>

Credential ID: `UC-1978d36f-352e-4168-b795-cf2526598547`

### Free Embedded Systems Course

<a href="./simplilearn-embedded-systems.pdf"><img src="./simplilearn-embedded-systems.jpg" alt="Simplilearn SkillUp Embedded Systems course completion certificate awarded to Nirzor Deb Opi on 23 October 2026." width="100%" /></a>

Certificate code: `10930187`

</details>

<a name="learning-goals"></a>
<h2><img src="./heading-learning-goals.gif" alt="Learning Goals" width="100%" /></h2>

My next learning priorities build on the projects above, with an emphasis on deeper independent implementation and system-level understanding.

| Direction | Next project goal |
| --- | --- |
| **Connected devices** | Publish ESP32 sensor measurements over MQTT |
| **Visualization & control** | Create a Node-RED dashboard for remote device control |
| **Embedded Linux** | Cross-compile C applications and explore Raspberry Pi GPIO |
| **Firmware reliability** | Practice fault handling, validation, and repeatable tests for STM32 peripherals and startup code |

<a name="opportunities"></a>
<h2><img src="./heading-opportunities.gif" alt="Opportunities" width="100%" /></h2>

I am seeking an **embedded software / embedded systems internship or thesis opportunity in Finland**. My interests include embedded C, ARM Cortex-M, firmware debugging, device drivers, real-time systems, and connected devices.

If your team is working in these areas, I would be happy to discuss how I can contribute and learn.

<p align="center">
  <a href="mailto:nirzordeb79@gmail.com"><img src="./email-3d.svg" alt="Email Nirzor" width="160" /></a>
  <a href="https://www.linkedin.com/in/nirzor-deb-opi-635846336/"><img src="./linkedin-3d.svg" alt="Connect on LinkedIn" width="160" /></a>
</p>

<p align="center"><a href="mailto:nirzordeb79@gmail.com">nirzordeb79@gmail.com</a><br/><sub>Build. Debug. Understand.</sub></p>

<details>
<summary>Visual credits</summary>

Board animation: an AI-generated 3D product visualization based on the STM32F407 Discovery reference in [STMicroelectronics UM1472](https://www.st.com/resource/en/user_manual/um1472-stm32f4-discovery-stmicroelectronics.pdf). This is a portfolio illustration, not an exact CAD model or a technical component-placement reference.

</details>
