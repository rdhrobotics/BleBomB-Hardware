# BleBomB

**BleBomB** is a compact embedded device designed to generate **2.4 GHz noise** using an **NRF24 module** and the **MM32G0001A1T MCU**.

The device continuously transmits randomized packets in the 2.4 GHz band, which can create heavy interference for nearby wireless communications operating on the same frequency range.

## Overview

BleBomB is a fully embedded hardware project developed by **RDH Roboticss**.
This repository contains all the necessary **hardware design files** required to reproduce the device.

The system is built around a low-power microcontroller and a 2.4 GHz RF transceiver to produce rapid wireless transmissions.

## Hardware Components

* **MM32G0001A1T** Microcontroller
* **NRF24L01+** 2.4 GHz RF Transceiver
* Embedded PCB Design

## Features

* Compact embedded design
* Generates 2.4 GHz RF noise using NRF24 transmissions
* Low-power MCU control
* Open hardware design files included

## Repository Contents

This repository includes:

* **KiCad project files**
* **PCB layout**
* **Schematic diagrams**
* **Gerber files** for PCB manufacturing
* Hardware source files

## Development

The hardware was designed using **KiCad** and optimized for a small embedded form factor.

## Disclaimer

This project is intended **for educational and research purposes only**.
Users are responsible for ensuring compliance with their **local laws and regulations regarding RF transmissions**.

## Author

Developed by **RDH Roboticss**
