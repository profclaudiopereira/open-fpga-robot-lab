
# 02 - FPGA Basics

<p align="center">
  <img src="../../../images/open_fpga_robot_lab_banner.png">
</p>

# Introduction

In this module we will learn the basic concepts of FPGA development.

Topics include:
- digital logic
- clocks
- registers
- combinational logic
- sequential logic
- FSM
- parallel processing

---

# What Makes FPGA Different?

Traditional microcontrollers execute instructions sequentially.

FPGA devices execute hardware logic in parallel.

This means:
- multiple operations at the same time
- deterministic timing
- high-speed processing
- hardware customization

---

# Digital Logic

FPGA systems are built using digital logic.

Basic logic elements:
- AND
- OR
- XOR
- NOT

These blocks form larger digital systems.

---

# Clocks

The clock synchronizes FPGA logic.

The DE0-Nano board includes:
- 50 MHz onboard clock

Used for:
- counters
- timers
- FSM
- communication interfaces

---

# Registers

Registers store digital values.

Examples:
- counters
- state machines
- temporary data

Registers change on clock edges.

---

# Combinational Logic

Output depends only on current inputs.

Example:
- logic gates
- arithmetic operations

---

# Sequential Logic

Output depends on:
- current inputs
- previous states

Examples:
- counters
- FSM
- memories

---

# Finite State Machines (FSM)

FSMs are fundamental in FPGA design.

Used for:
- robot control
- communication protocols
- automation
- embedded systems

---

# Parallel Processing

One of the biggest FPGA advantages.

Example:
- UART can run
- PWM can run
- sensor processing can run

All simultaneously.

---

# Verilog Example

Simple LED toggle example:

```verilog
module blink (
    input clk,
    output reg led
);

always @(posedge clk)
begin
    led <= ~led;
end

endmodule
```

---

# Educational Goals

After this module you should understand:
- FPGA basics
- clock behavior
- digital logic
- parallel execution
- simple Verilog structure

---

# Next Module

Continue to:

## 03_quartus_installation
