# GPIO-IP-Core-AMBA-APB
Design and verification of a configurable GPIO IP Core with an AMBA APB slave interface using Verilog HDL.



## Project Overview

Designed and developed a configurable General-Purpose Input/Output (GPIO) IP Core with an AMBA Advanced Peripheral Bus (APB) slave interface using Verilog HDL.

The project focuses on integrating GPIO functionality with a standard AMBA APB communication interface, enabling processor-based systems to access and control GPIO registers through bus transactions.

## Architecture

The design consists of the following major modules:

APB Slave Interface: Handles APB bus communication and read/write transactions.

GPIO Register Block: Manages GPIO configuration and data registers.

Auxiliary Interface: Provides an optional auxiliary input path with synchronization logic.

I/O Interface: Handles input and output pad signals, including tri-state control.

GPIO Top Module: Integrates all submodules into a complete GPIO IP Core.

## Key Features

AMBA APB slave interface integration.

Configurable GPIO input/output functionality.

Register-based GPIO control.

Auxiliary input support.

Tri-state I/O interface.

Modular and synthesizable RTL architecture.

## Tools and Technologies

HDL: Verilog

Simulation: ModelSim

Synthesis: Intel Quartus Prime Lite Edition

Protocol: AMBA APB

## Verification and Implementation

Developed individual RTL modules and integrated them into the complete GPIO architecture.

Created Verilog testbenches to verify module functionality.

Performed functional simulation and waveform analysis using ModelSim.

Conducted RTL synthesis and debugging using Quartus Prime Lite Edition.
