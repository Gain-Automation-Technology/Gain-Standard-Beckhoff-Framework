# <p align="center"><img src="docs/assets/gain-logo-header-crop.png" alt="Gain Automation Logo" width="275"/></p>

# Gain Standard Beckhoff Library (GSBF)


## What is GSBF?

The **Gain Standard Beckhoff Framework (GSBF)** is a modular, open-source library suite for Beckhoff TwinCAT automation projects. It provides reusable libraries, best practices, and tools to accelerate industrial automation development.

**Example use:**
> Use GSBF to quickly build a modular, maintainable TwinCAT PLC project for a packaging line, including motion control, HMI, and advanced diagnostics, by combining only the modules you need.

---


## Getting Started

1. Download the latest compiled GSBF libraries from the [GitHub Releases](https://github.com/Gain-Automation-Technology/Gain-Standard-Beckhoff-Framework/releases) page.
2. Add the required GSBF libraries to your TwinCAT XAE project.

---

## Submodules & Feature Highlights

GSBF is split into several libraries. Only **GSBF_Common** is always required; all others are optional and can be added as needed.

| Library         | Description                                                      | Feature Highlights                                                                 | Wiki Overview Page                                  |
|-----------------|------------------------------------------------------------------|-------------------------------------------------------------------------------------|-----------------------------------------------------|
| GSBF_Common     | Core types, utilities, and base function blocks.                 | Alarms, base motion, motor/valve control, e.g. `CM_Motor_Base`, `CM_Valve_Base`, `FB_AlarmHandler` | [GSBF_Common Wiki](https://github.com/Gain-Automation-Technology/Gain-Standard-Beckhoff-Framework/wiki/GSBF_Common-library)           |
| GSBF_HMI        | HMI integration and visualization helpers.                       | HMI helpers for motors, valves, servos, e.g. `HMI_CM_MotorDol`, `HMI_CM_Servo`      | [GSBF_HMI Wiki](https://github.com/Gain-Automation-Technology/Gain-Standard-Beckhoff-Framework/wiki/GSBF_HMI-library)              |
| GSBF_Camming    | Camming and motion profile generation.                           | Camming profile generation, servo add-ons, e.g. `CM_Servo_CammingAddon`             | [GSBF_Camming Wiki](https://github.com/Gain-Automation-Technology/Gain-Standard-Beckhoff-Framework/wiki/GSBF_Camming-library)          |
| GSBF_FlyingSaw  | Flying saw and synchronized cutting applications.                | Flying saw synchronization, servo add-ons, e.g. `CM_Servo_FlyingSawAddon`           | [GSBF_FlyingSaw Wiki](https://github.com/Gain-Automation-Technology/Gain-Standard-Beckhoff-Framework/wiki/GSBF_FlyingSaw-library)        |
| GSBF_License    | Licensing and feature management for GSBF-based solutions.       | License management, feature control, e.g. `FB_LicenseManager`                       | [GSBF_License Wiki](https://github.com/Gain-Automation-Technology/Gain-Standard-Beckhoff-Framework/wiki/GSBF_License-library)          |

---
