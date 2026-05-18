# Hi there 👋, I'm Marwan Khaled Mohamed Ryad

**Digital Design & Verification Engineer**

I am an Electronics and Communication Engineering graduate from Cairo University, passionate about building and verifying complex digital systems. With a solid foundation in hardware/software co-design, SoC architectures, and advanced DSP, I specialize in bringing high-performance RTL designs to life and ensuring their robustness through rigorous UVM environments.

## 🎓 About Me
* 📚 **Education:** B.Sc. in Electronics and Communication Engineering, Cairo University (Excellent Grade, 86.6%).
* 🎯 **Focus Areas:** RTL Design, UVM Verification, ASIC/FPGA Flow, and HW/SW Co-design.
* 💼 **Experience:** * **Digital Design Intern** at Analog Devices (ADI).
  * **Digital Verification Intern** at Mixel.
* 📫 **Contact:** khaledryad816@gmail.com

## 🛠️ Technical Skills
* **HDLs & Verification:** Verilog, VHDL, SystemVerilog, UVM, Assertions (SVA), Functional & Code Coverage.
* **Digital Design & Physical Flow:** RTL Design, Logic Synthesis, CDC, STA, FPGA Design Flow, ASIC Flow (RTL-to-GDS).
* **SoC & Bus Architectures:** Computer Architecture, HW/SW Co-design, Bus Protocols (AMBA APB/AHB/AXI).
* **Signal Processing & Scripting:** MATLAB, DSP System-Level Modeling, Fixed-Point Analysis, Python, C/C++, TCL, Shell Scripting.
* **EDA Tools:** Questa Sim, ModelSim, Xilinx Vivado, Synopsys Design Compiler, Cadence Virtuoso.

## 🚀 Featured Digital Design & Verification Projects

### 1. Hardware-Accelerated Massive MIMO Detection System (Graduation Project)
* Designed a hardware-accelerated 8x8 MIMO detection system for 5G/6G networks using a Multi-Cluster PULP Platform.
* Architected a multi-accelerator subsystem by deploying 8 Hardware Processing Engines (HWPEs) using an SDF FFT core.
* Investigated HW/SW execution flows and traced instructions routed from the controller's main memory to a shared cache via an AXI bus.
* Traced hardware DMA data paths, identifying transfer bottlenecks to justify scaling to a multi-cluster architecture.
* Implemented a Matched Filter and linear solver-based matrix inversion architecture integrated with a systolic array matrix multiplier for a full MMSE equalizer.

### 2. RTL-to-GDS Low-Power Multi-Clock Digital System
* Designed core system blocks from scratch (ALU, FIFO, UART, Synchronizers) and verified logic using a SystemVerilog self-checking testbench.
* Constrained and synthesized the design using Synopsys Design Compiler (TCL scripts), resolved setup/hold violations, and proved functional equivalence via Formality before executing the complete ASIC physical flow to GDS.

### 3. System-on-Chip (SoC) Design & Bus Architectures
* Implemented a 50-instruction pipelined MIPS processor (along with 10-instruction multi-cycle and 50-instruction single-cycle variants) featuring exception handling and branch prediction units.
* Integrated an APB/AHB bus architecture with an AHB-to-APB bridge controlling peripherals like a Timer and GPIO.

### 4. AMBA AHB-Lite Protocol Implementation
* Designed an end-to-end Single-Master AMBA AHB-Lite Protocol from RTL design to FPGA implementation flow using Xilinx Vivado.

### 5. Advanced UVM & SystemVerilog Verification Projects
* **ALSU Verification:** Designed the RTL and developed a comprehensive UVM-based verification environment for an Arithmetic Logic Shift Unit.
* **PWM Verification:** Implemented the RTL for a Pulse Width Modulation unit, verified it via a UVM environment, and deployed it on an FPGA.
* **FIFO UVM Verification:** Fully verified a FIFO design using a complete UVM environment with functional and code coverage metrics.
* **FIFO SystemVerilog Verification:** Implemented constrained randomization, assertions (SVA), and a golden model for FIFO verification.

### 6. Clock Domain Crossing (CDC) & Specialized Arithmetic Units
* **Configurable Cross-Clock Domain Unit:** Engineered a highly parameterized RTL architecture with an Asynchronous FIFO for safe data transfer across unrelated clock domains.
* **Configurable Kogge-Stone Adder:** Implemented a fully configurable 16-bit Parallel Prefix Adder utilizing a custom dot-operator tree to minimize arithmetic delay.
* **Asynchronous FIFO:** Designed and implemented an Asynchronous FIFO utilizing advanced CDC techniques, fully deployed on an FPGA.

### 7. Hardware Accelerators & Peripheral IPs
* **3×3 Systolic Array:** Executed a full-custom transistor-level design of a systolic array architecture for matrix multiplication.
* **DSP48A1 Slice Design:** Modeled and designed a DSP48A1 slice matching Spartan-6 FPGA architecture using Verilog.
* **SPI Slave with RAM:** Implemented an SPI Slave protocol integrated with a single-port RAM on an FPGA.
