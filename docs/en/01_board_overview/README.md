
# DE0-Nano Board Overview

<p align="center">
  <img src="../../../images/open_fpga_robot_lab_banner.png">
</p>

## Introduction

The Terasic DE0-Nano is an educational FPGA development board based on the Intel/Altera Cyclone IV FPGA family.

This board is widely used in:
- digital systems education
- robotics
- embedded systems
- signal processing
- hardware acceleration
- FPGA learning

---

# What is an FPGA?

FPGA means:

> Field Programmable Gate Array

Unlike a traditional microcontroller, an FPGA executes hardware circuits in parallel.

This allows:
- real parallel processing
- high-speed logic
- custom hardware architectures
- hardware acceleration

---

# Main Components

## Cyclone IV FPGA

The main chip on the board.

Responsible for:
- digital logic
- state machines
- counters
- communication interfaces
- custom hardware

---

## USB-Blaster

Used to:
- program the FPGA
- send bitstreams
- debug projects

---

## LEDs

Useful for:
- debugging
- first FPGA projects
- hardware visualization

---

## GPIO

Allows connection with:
- sensors
- displays
- motors
- ESP32
- robotics modules

---

## Accelerometer (ADXL345)

Measures:
- movement
- tilt
- acceleration

Useful for:
- robotics
- balancing systems
- motion detection

---

# Typical FPGA Development Flow

1. Create HDL project
2. Write Verilog code
3. Compile design
4. Configure FPGA pins
5. Generate bitstream
6. Program FPGA
7. Test hardware

---

# Educational Goals

This project was created to provide:
- step-by-step tutorials
- practical FPGA learning
- multilingual documentation
- modern educational material

---

# Next Module

Continue to:

## 02_fpga_basics

Where we will learn:
- clocks
- digital logic
- registers
- FSM
- parallel processing
