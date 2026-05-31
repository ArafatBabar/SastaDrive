# SastaDrive Rev 1

![alt text](<ESC Drive 1.png>)

## Overview

SastaDrive Rev 1 is a 3-Phase Field-Oriented Control (FOC) capable motor driver developed under Mekatra.

The project was created to explore practical motor control hardware design, power electronics, current sensing, embedded firmware development, and PCB layout techniques using the STM32G431 microcontroller.

This revision represents the first complete iteration of the platform and served as the foundation for future developments including Axelleron Rev 2.

---

## Key Features

- STM32G431CBUx MCU
- 3-Phase MOSFET Inverter
- UCC27710 Gate Drivers
- Inline Phase Current Sensing
- DC Bus Voltage Monitoring
- DC Bus Current Monitoring
- CAN Bus Interface
- Encoder Interface
- SWD Debug Support
- UART Communication
- Onboard Power Conversion

---

## Specifications

| Parameter | Value |
|------------|------------|
| Input Voltage | 18V - 26V |
| Nominal Voltage | 24V |
| Continuous Current | 5A |
| Peak Current | 10A |
| Control Method | FOC Capable |
| MCU | STM32G431 |
| Communication | CAN, UART |
| Encoder Support | AS5600 |

---

## Design Goals

- Learn practical motor control hardware design
- Develop a compact FOC-capable platform
- Explore embedded motor control firmware
- Create a reusable architecture for future revisions

---

## Known Limitations

This repository documents the first revision of the design.

Known limitations include:

- Limited protection features
- No reverse polarity protection
- Layout optimizations identified after design review
- Thermal improvements required
- Additional fault handling needed

Several improvements have already been incorporated into the successor project:

**Axelleron Rev 2**

---

## Status

Archived Development Revision

Not recommended for production use.

Provided for educational, documentation, and portfolio purposes.

---

## Images

### Front

![alt text](<ESC Drive 1-1.png>)

### Back

![alt text](<ESC Drive back 1.png>)

---

## Lessons Learned

SastaDrive Rev 1 taught valuable lessons in:

- Power electronics
- Gate driver design
- Current sensing
- PCB layout
- Thermal design
- EMC considerations
- Hardware documentation
- Design-for-manufacture practices

These lessons directly influenced the development of Axelleron Rev 2.

---

## Design Review Notes

This design is not perfect.

Several shortcomings were identified after completion of Rev 1, including protection architecture, layout optimization opportunities, and thermal improvements.

These findings became the basis for Axelleron Rev 2.

The repository is intentionally preserved in its original state as a record of the design process and lessons learned.

## License

Hardware and documentation are released under the CERN-OHL-S license unless otherwise specified.
