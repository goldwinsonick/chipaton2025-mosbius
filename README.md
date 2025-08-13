# Team Prof Morbius : An FHSS Educational Learning Kit Project

## Overview

Welcome to the chipaton2025-mosbius repository!

This repository contains all the design files, documentation, and progress for our Frequency Hopping Spread Spectrum (FHSS) Educational Learning Kit. With this project, we aim to create a hands-on platform for teaching students the system-level principles of spread spectrum communication.

This project is our team's submission for the SSCS Chipathon 2025 (MOSBius Track). We are Team Prof Morbius from the Institute of Technology Bandung, Indonesia.

## The Project

The goal of this project is to create the **reconfigurable mixer** and **PN sequence generator** for **FHSS Educational Learning Kit**.

This educational kit is composed of two main parts:

1. **The FHSS Learning Kit Module**: A hardware platform including a custom-designed IC (Mixer and PN Sequence generator), a PCB with all necessary analog circuits, and the MOSBius chip for experimentation.

2. **The Practicum Guide**: A comprehensive laboratory manual that guides students through experiments to understand FHSS concepts from the ground up.

To learn more about the development and documentation, you can refer to these sources.

- Our [**Revised Prof Morbius Proposal**](https://drive.google.com/file/d/1uSmN1Kq2bPWWUJlL5vvVy811TZmL9LWt/view?usp=sharing) contains the explanation about the project's plan and detail. (The document also contains the detail about the pinlist, block diagrams, and project tracker)

- The Learning Kit will consist of Custom Chip Design and PCB Design that contains everything needed for the FHSS System. For the FHSS Learning Kit Module, please refer to [**FHSS Learning Kit**](./docs/system_architecture.md)

- For the FHSS Practicum Guide Module, please refer to [**FHSS Laboratory Module**](https://drive.google.com/file/d/1QCHJ8PP__YJWEzheR70c9E-Kh2Sm1mwg/view?usp=sharing)

Implementation and Verification for On-Chip Design is done in the [**prof-morbius-rf-chip**](https://github.com/orpheus016/prof-morbius-rf-chip) repository.

## Pin Out and Estimated Die Size

Below are the specifics for our chip

### **Chip Diagram**
<img width="1074" height="603" alt="image" src="https://github.com/user-attachments/assets/d0b4bd6f-b3f1-494b-8c09-299ffa4ecb3b" />

### **Pin List**

Physical Specification:
* Estimated Die Size = 0.64 mm²
* Pin Out Total = 18 Pins inclluding power source and grounds
