\# Verilog Electronic Voting Machine



\## Overview



A Verilog HDL based Electronic Voting Machine designed using a finite state machine (FSM).



\## Features



\- Four candidate selection

\- Vote counting

\- FSM-based control

\- Reset functionality

\- Winner determination

\- Simulation and waveform verification

\- RTL synthesis using Yosys



\## Project Structure



\- `voting\_machine.v` - Main Verilog RTL design

\- `voting\_machine\_tb.v` - Testbench for simulation

\- `synth.ys` - Yosys synthesis script



\## FSM



The design uses multiple states to control the voting process:



```text

IDLE

&#x20; ↓

AUTHENTICATE

&#x20; ↓

VOTING

&#x20; ↓

COUNT

&#x20; ↓

RESULT

