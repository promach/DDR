# DDR
A simple DDR3 memory controller for [Micron DDR3 RAM](https://www.micron.com/products/dram/ddr3-sdram/part-catalog/mt41k64m16tw-107)

TODO:
1. Debug the low-speed waveform when the DDR3 FPGA board arrives.
2. Implement [Type-III digital PLL described in Floyd Gardner book: Phaselock Techniques, 3rd Edition](https://www.reddit.com/r/AskElectronics/comments/9i7g9j/loop_stability_of_type_3_digital_pll/) for high-speed application and `DQS` phase-shift purpose
3. Investigate high-speed DDR PHY IO as described in reference \[1\], [2], [3], [4], [5]
4. Design my own DDR3 FPGA board

Credit: [@Morin](https://github.com/MartinGeisse) and [@Greg](https://github.com/gregdavill/) for their helpful technical help and explanation

Reference:

\[1]: [Preamble detection and postamble closure for a memory interface controller](https://patents.google.com/patent/US8023342)

\[2]: [Circuit design technique for DQS enable/disable calibration](https://patents.google.com/patent/US9158873)

\[3]: [Dqs generating circuit in a ddr memory device and method of generating the dqs](https://patents.google.com/patent/KR20050101864A/en)

\[4]: [DQS strobe centering (data eye training) method](https://patents.google.com/patent/US7443741B2/en)

\[5]: [Data strobe enable circuitry ](https://patents.google.com/patent/US9001595)
