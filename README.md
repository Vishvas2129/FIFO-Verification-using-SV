# FIFO-Verification-using-SV


## Overview 

This project focuses on the functional verification of a FIFO (First-In-First-Out) design using SystemVerilog. The verification environment follows industry-standard methodologies and ensures the correctness of the FIFO design under various test conditions.

## Testbench Architecture

The testbench follows a modular approach with the following components:

1. FIFO DUT (Design Under Test): The RTL implementation of FIFO.

2. Testbench Environment: Manages stimulus generation and response checking.

3. Driver: Sends write/read commands to FIFO.

4. Monitor: Captures transactions for analysis.

5. Scoreboard: Compares expected and actual results.

6. Assertions: Ensures protocol compliance and data integrity.
