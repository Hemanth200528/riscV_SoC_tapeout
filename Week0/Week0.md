# Week 0: Installation of Yosys, Icarus Verilog & GTKWave

## System Specifications
- Minimum 6 GB RAM
- Minimum 50 GB HDD space
- Ubuntu 20 or later (recommended: VM via Oracle VirtualBox or Windows WSL)

---

## Tools Overview

### <img src="./images/Yosys.png" alt="Yosys Logo" width="40" /> Yosys
Yosys is an open-source RTL synthesis tool that converts Verilog designs into gate-level netlists. It is widely used for digital logic synthesis and preparing designs for hardware implementation.

#### Installation
Before installing, make sure `git` and `make` are installed:
```bash
sudo apt install git
sudo apt-get install make
