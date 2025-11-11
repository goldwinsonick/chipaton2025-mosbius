# System Architecture

The system we are imagining includes the modulated FSK signal as the input and demodulated signal as the output. More detail on this diagram.

<p align="center">
    <img src="./assets/diagram_system_architecture.png">
</p>

The learning kit is partitioned into three main implementation domains:

1. **On-Chip (Custom IC)**: Core analog blocks that are fundamental to the learning objectives are designed and implemented in a custom IC. This includes the **PN Sequence Generator** and the **Gilbert Cell Mixer**.

    Refer to the [**On-Chip System Design Page**](./system_on_chip.md) for more information

2. **Off-Chip (PCB)**: Supporting systems like the **VCO/PLL**, **FSK modulation**, **FSK demodulation**, and **noise generation** are implemented using COTS components and analog circuits on a central PCB.

    Refer to the [**Off-Chip System Design Page**](./system_off_chip.md) for more information

3. **MOSBius Playground**: The **MOSBius chip** acts as the central hub and configurable switch matrix, connecting all the blocks and providing a flexible platform for students to reconfigure the system and conduct experiments.