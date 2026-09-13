<div align="center">

# Inauguration Welcome Robot

**ESP32 mobile greeting robot with movement, obstacle sensing, animated feedback and audio.**

![Status](https://img.shields.io/badge/status-prototype_iteration-F0A44B?style=flat-square)
![Platform](https://img.shields.io/badge/platform-ESP32_%C2%B7_Robotics-101820?style=flat-square)
![Brand](https://img.shields.io/badge/by-RA_TECH-101820?style=flat-square)

</div>

## Overview

A mobile welcome robot designed for event inauguration and guest greeting. It combines drive motors, arm movement, obstacle sensing, display messages, LED eyes, and recorded audio in one ESP32-controlled system.

> **Project status:** Prototype iteration

## Highlights

- Forward, reverse, left, and right movement
- Independent arm up and down control
- Ultrasonic obstacle awareness
- Welcome messages on an I2C LCD
- LED eye feedback
- DFPlayer-based greeting audio

## Hardware

| Component | Role |
|---|---|
| ESP32 development board | Main processing and control |
| Two L298N motor drivers | Project subsystem |
| Two drive motors and two arm motors | Project subsystem |
| HC-SR04 ultrasonic sensor | Project subsystem |
| 16×2 I2C LCD | Project subsystem |
| DFPlayer Mini, amplifier, and speaker | Project subsystem |
| LED eyes and suitable power system | Project subsystem |

## Repository structure

```text
inauguration-welcome-robot/
├── firmware/   Tested source code and configuration notes
├── hardware/   Wiring, components, PCB, and enclosure information
├── docs/       Build guide, calibration, results, and troubleshooting
├── media/      Prototype images, diagrams, and demo links
└── README.md   Project overview and release status
```

## Current public release

This initial release establishes the verified project overview and a clean documentation structure. Firmware, wiring diagrams, and media will be added only after each item is checked for accuracy and private credentials are removed.

## Roadmap

- [ ] Document the final power-distribution upgrade
- [ ] Publish the stable motor-control firmware
- [ ] Add the complete pin map without rewiring
- [ ] Add enclosure photos and a demonstration video

## Safety and reproducibility

- Verify every supply voltage before powering the controller or modules.
- Use a common ground and a power source sized for peak motor or audio current.
- Never commit Wi-Fi passwords, API keys, personal contact details, or certificates.
- Recheck the published pin map against the tested hardware before assembly.

---

<div align="center">

**Designed and developed by [Rohi · RA TECH](https://github.com/Rohibuilds)**

<sub>Build. Test. Improve. Share.</sub>

</div>
