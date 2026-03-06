# Low-Power-Dual-Read-RAM-2R1W
Dual Read, Single Write(2R1W)64x8 RAM in Verilog with clock gating and active-low reset.
->Overview
This project implements a Dual-Read, Single-Write (2R1W) RAM in Verilog HDL.
Size: 64 words × 8 bits
Ports: 2 independent read ports, 1 write port
Features:
Clock gating for power efficiency
Active-low reset for initialization
Synchronous design suitable for FPGA/ASIC flows
This design is useful in multi-processor systems, parallel data access architectures, and VLSI design learning projects.

->Design Specifications
Write Port (W):
Address: 6-bit (supports 64 locations)
Data In: 8-bit
Write Enable: Active-high
Read Ports (R1, R2):
Independent 6-bit addresses
Data Out: 8-bit each
Reset:
Active-low (reset_n)
Clears memory contents
Clock Gating:
Write operations only occur when clock is enabled
Reduces dynamic power consumption

->Applications
Multi-core processor memory systems
Parallel data access in DSP/IoT
Educational VLSI design projects
