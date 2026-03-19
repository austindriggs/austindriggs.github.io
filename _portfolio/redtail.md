---
title: "RedTail LiDAR"
excerpt: "Over 3 years of experience designing, assembling, and testing printed circuit boards (PCBs) in RedTail LiDAR systems."
collection: portfolio
---

---

While in undergrad at WVU, I worked part time (~20 hours a week) at [4D Tech Solutions](https://4dtechsolutions.com) (a cleared government contracting company) as an Electronics Engineer designing, assembling, and testing printed circuit boards (PCBs) in [RedTail LiDAR](https://redtaillidar.com) systems.


## WHAT IS LIDAR?

LiDAR (Light Detection And Ranging), similar to RADAR and SONAR, uses laser pulses to measure distances with high precision, creating detailed 3D point clouds of the environment. It’s used in a variety of applications such as autonomous vehicles, surveying, and defense systems.

A couple of good resources to learn and see more are:
1. A demo video is shown on the RedTail LiDAR [home page](https://www.redtaillidar.com/).
2. A video of the internals of the RTL-450 is shown on the [product page](https://www.redtaillidar.com/product).
3. Different use cases can be found on the [applications page](https://www.redtaillidar.com/applications).


## RTL-450 RECON

Throughout my time at 4D Tech, our primary goal was to develop the next generation LiDAR system, the [RTL-450 Recon](https://www.redtaillidar.com/insights/redtail-lidar-exhibits-at-sof-week-2025-and-xponential-2025), which supports rapid reconfigurability in aerial, handheld, and tripod modes of operation, while also offering a reduced weight and size at 4lbs and 8" x 5" x 4" volume. On top of all of the user enhancements, the system also has more processing power and better dynamic range.

I was responsible for designing approximately half of the PCBs inside the RTL-450 Recon, and contributed to all of them through either testing, review, and/or documentation. Some skills I learned and tools I worked with include:
- Design and Development in KiCad: Schematic and layouts for mixed signal PCBs from 4 to 12 layers with high-current delivery (up to 10 Amps) alongside sensitive low-noise signals.
- Routed High-Speed Protocols: I2C, SPI, UART, USB 2.0, LVDS, SGMII/RGMII Ethernet, SATA, PPS and NMEA.
- Component Integration: Xilinx FPGAs/SOMs, TI ADCs, STM32 and RP2040 microcontrollers, Applanix APX-18 IMU, Power Management ICs, EEPROMs, SD cards, Photodiodes.
- Soldering and Assembly: Hundreds of prototype and production PCBs containing fine-pitch SMD (0402), high-density BGAs, QFNs, and more.
- Test Setups and Procedures: Benchtop power supplies, oscilloscopes, load supplies, MEMS mirrors and 1550nm pulsed laser diode drivers, custom test PCBs, and automated the rapid development setups using Python/Micropython.
- Configuration Management: Maintained notes for all designs, BOMs, library management, trace impedance and length tuning calculations, CI/CD concepts using Docker and KiBot, and version control change logs using Git/GitLab.

> *While I cannot publically display the PCBs I designed at 4D, I designed the [Payload PCB for URC](https://austindriggs.github.io/portfolio/urc/) during my senior year capstone at WVU, where I applied the same design principles and practices I learned during my time at 4D.*
