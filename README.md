# VLSI RTL Design - Verilog

<p align="center">
  Learning and implementing RTL design using Verilog, with testbench simulations and basic VLSI modules.
</p>

---

## 🎯 Purpose
This repository focuses on **VLSI RTL design using Verilog**.  
It contains modules for combinational and sequential circuits, finite state machines (FSMs), and testbench simulations to understand digital design at the RTL level.

---

## 📚 Contents
- Combinational Circuits (Adder, Subtractor, Multiplexer, etc.)  
- Sequential Circuits (Flip-Flops, Counters, Shift Registers)  
- Finite State Machines (FSMs)  
- Testbench Simulations  
- Waveform Outputs  
- Notes & Observations  

---

## 🧭 Learning Roadmap

**Combinational Circuits**
- [ ] Half Adder / Full Adder  
- [ ] Multiplexer / Demultiplexer  
- [ ] Encoder / Decoder  

**Sequential Circuits**
- [ ] Flip-Flops (D, T, JK, SR)  
- [ ] Counters  
- [ ] Shift Registers  

**FSM & Advanced**
- [ ] Simple FSM design  
- [ ] State diagram → Verilog implementation  

**Simulation & Testing**
- [ ] Testbench basics  
- [ ] Waveform verification  
- [ ] Timing analysis  


## 🧩 VLSI System Overview

This flowchart represents the **RTL design and simulation process** for VLSI projects.  
It shows how your Verilog RTL modules and testbenches are compiled, simulated, and produce waveform outputs.

### RTL design and verification using free source EDA plaground
```mermaid
flowchart LR
    RTL_DESIGN_TESTBENCH -->|Compile & Check| EDA_PLAYGROUND
    EDA_PLAYGROUND -->|Simulate| TOOLS_SIMULATOR
    TOOLS_SIMULATOR -->|Waveform Output| SIMULATION_OUTPUT
