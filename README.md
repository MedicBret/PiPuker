# PiPuker
Simulation Difficult Airway with fluid flow
# PiPuker

PiPuker is a Raspberry Pi-based vomit simulator designed for EMS, military, and technical rescue training environments. It offers a realistic, hands-on experience for students learning patient care in austere or high-stress scenarios.

## 🧪 Purpose

The goal of PiPuker is to simulate emesis during trauma, medical, or tactical scenarios. It enhances realism and prepares providers to respond effectively under challenging conditions.

## ⚙️ Features

- Raspberry Pi Zero 2 WH controlled emesis simulation
- Peristaltic pump activation for fluid discharge
- Push-button triggered with LED status indicator
- Powered via 12V/5V TalentCell battery pack or wall adapter
- Compact and modular for field or classroom use
- Open source and customizable for expanded use cases

## 🧰 Hardware Components

- Raspberry Pi Zero 2 WH
- TIP120 NPN Darlington transistors
- 12V 3A power supply
- 12V/5V TalentCell battery pack
- Peristaltic pump (Kamoer KPRP20)
- DC-DC buck converter
- LED push button switch
- 1N4007 diodes
- Resistors, jumper wires, breadboards
- 500ml wash bottles, silicone tubing, plastic hose barb connectors, and check valves
- ABS project enclosure

## 🛠️ Software

- Python 3
- GPIO Zero and RPi.GPIO libraries
- Systemd service for autorun
- Optional Flask server for remote control or instructor interface

## 🚀 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/MedicBret/PiPuker.git
   cd PiPuker
## Install Dependencies
sudo apt update
sudo apt install python3-gpiozero python3-rpi.gpio

## Run the simulator
python3 pipuker.py

## MIT License
MIT License

Copyright (c) 2025 Bret Mitchell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
