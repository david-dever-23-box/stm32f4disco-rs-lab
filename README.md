# stm32f4disco-rs-lab

Personal lab monorepo containing Rust applications and crates for the STMicroelectronics
[STM32F4DISCOVERY](https://www.st.com/en/evaluation-tools/stm32f4discovery.html) development board,
featuring the 72 MHz [STM32F405xx/STM32F407xx](https://www.st.com/resource/en/datasheet/stm32f407vg.pdf)
family of Arm(R) Cortex(R)-M4 MCUs with FPU.

---

## `STM32F407VGT6`

### General Description

_The `STM32F405xx` and `STM32F407xx` family is based on the high-performance Arm(R)
Cortex(R)-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex(R)-M4
core features a single-precision floating point unit (FPU) which supports all Arm single-
precision data-processing instructions and data types. It also implements a full set of DSP
instructions and a memory protection unit (MPU) which enhances application security._

_The `STM32F405xx` and `STM32F407xx` family incorporates high-speed embedded
memories (flash memory up to 1 Mbyte, up to 192 Kbytes of SRAM), up to 4 Kbytes of
backup SRAM, and an extensive range of enhanced I/Os and peripherals connected to two
APB buses, three AHB buses and a 32-bit multi-AHB bus matrix._

_All devices offer three 12-bit ADCs, two DACs, a low-power RTC, twelve general-purpose
16-bit timers including two PWM timers for motor control, two general-purpose 32-bit timers.
a true random number generator (RNG). They also feature standard and advanced
communication interfaces._

### Reference Manual

* [RM0090 Reference manual](https://www.st.com/resource/en/reference_manual/rm0090-stm32f405415-stm32f407417-stm32f427437-and-stm32f429439-advanced-armbased-32bit-mcus-stmicroelectronics.pdf), includes: 
  * `STM32F405 / F415`
  * `STM32F407 / F417`
  * `STM32F427 / F437`
  * `STM32F429 / F439`
  
---

## Getting Started

### Required Hardware

>The following instructions assume, for simplicity, the existence of an available USB Type-A port on the host device. Use of an adapter providing a USB Type-A port to USB-C connector should also work.

A **USB Mini-B to Type-A cable** is required for connection between the development board and the host device. The USB Mini-B connector plugs into the USB Mini-B port, flat side up, i.e., away from the PCB.

![USB Mini-B port](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/USB_Mini-B_receptacle.svg/134px-USB_Mini-B_receptacle.svg.png)

![USB Type-A connector](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c5/USB_Type-A_receptacle_Black.svg/150px-USB_Type-A_receptacle_Black.svg.png)

### Required Software

#### macOS

>TODO

#### Windows

>TODO

#### Linux

>TODO

---

## License

[MIT License](https://spdx.org/licenses/MIT.html)

---

`./README.md`
