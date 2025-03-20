# Dynamic Carry Look-Ahead Adder (CLA)

## Overview
This project implements an optimized Dynamic Carry Look-Ahead Adder (CLA) using a 300nm 5-metal layer CMOS process. The design enhances traditional static adders by leveraging dynamic logic, achieving high-speed performance, reducing transistor count, and optimizing area while balancing power consumption.

## Key Features
- Faster Computation: Dynamic logic significantly reduces propagation delay.
- Optimized Area: Fewer transistors result in a more compact design.
- Efficient Performance: Balances speed and area with a slight trade-off in power consumption.

## Performance Improvements
Compared to conventional 8x8-bit adders, the Dynamic CLA offers notable enhancements:

### Speed Improvement:
- 69.46% faster than Ripple Carry Adder.
- 57.44% faster than Traditional CLA.
- Achieves a delay of 1.285 ns, significantly faster than the Ripple Carry Adder 4.208 ns and Traditional CLA 3.02 ns.

### Area Reduction (Transistor Count):
- 34.72% smaller than Ripple Carry Adder.
- 49.46% smaller than Traditional CLA.
- The calculated area for the 8x8 CLA is 92,369 µm², optimized compared to conventional implementations.

### Power Consumption:
- The 8x8 CLA dissipates 5.09 µW, representing a necessary trade-off to achieve higher speed and efficiency.

## Project Files
- CLA_1bit.jelib - 1-bit CLA design
- CLA_4.jelib - 4-bit CLA design
- CLA_8bits.jelib - 8-bit CLA design
- Inverter.jelib - Supporting inverter logic
- NANDcla.jelib - NAND gate implementation for CLA
- XORcla.jelib - XOR gate implementation for CLA
- IC_paper.pdf - Detailed research paper on the project
