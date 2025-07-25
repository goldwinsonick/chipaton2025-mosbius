# chipaton2025-mosbius

## Overview

This repository contains the development for the [`SSCS Chipaton 2025`](https://github.com/sscs-ose/sscs-chipathon-2025) project from **Team Prof Morbius**.

The Team:
- James Patrick (Leader) 
- Ibrahim Hanif Mulyana 
- Goldwin Sonick Wijaya Thaha 

## The Project

The [**Frequency Hopping Spread Spectrum (FHSS)**](https://en.wikipedia.org/wiki/Frequency-hopping_spread_spectrum) is a wireless communication technique where the carrier frequency rapidly changes (or "hops") among many frequency channels
, following a specific sequence known to both transmitter and receiver.
This method enhances security, reduces interference, and improves resistance to jamming.

This project aims to implement IC Design Layout for the FHSS system. This system will be integrated with the [**MOSbius Chip**](https://mosbius.org/0_front_matter/intro.html) to create a Learning Kit for the FHSS System.

The system will look like this:
![]() <!-- Diagramnya -->

| Component | Implementation | Description |
|-|-|-|
| PN Generator  | On-Chip | Determines the next frequency channel for hopping by generating a pseudo-random sequence. |
| VCO           | On-Chip | Produces a variable-frequency carrier signal that can be rapidly tuned for frequency hopping. |
| PLL           | COTS    | Locks and stabilizes the frequency of the VCO, ensuring precise and stable frequency generation. |
| Mixer         | On-Chip | Combines (mixes) the carrier signal with the message signal to shift the message to the desired frequency band. |

For more information about the implementation, go to [**Project Implementation Description**](./docs/implementation.md)

# Results
- Schematic Simulation Result: [**Schematic Simulation Result**](./docs/simulation_result.md)

## Quick Links

Here are quick links to important files and folders.
- [`Project Timeline`]( https://docs.google.com/spreadsheets/d/1ED5GlzHhh6iyMfWsxwQK_LsvYb5z8FFv7d2K7-hli_0/edit?usp=sharing ) : Timeline for the development
- [`Project Proposal`]( https://docs.google.com/presentation/d/1d4etSCZGezYiTcyhqJMmxZKgGMZXT_DFGWo_tfqO1z0/edit?usp=sharing ) : Proposal for the Project
- [`Main Google Drive`]( https://drive.google.com/drive/folders/1l0VH1jhEloeevTNJNOWizoYGq4sh_gAN?usp=sharing ) : The main google drive for this project
