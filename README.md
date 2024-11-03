Developed a digital system capable of receiving commands through a UART receiver to perform system
functions such as register file reading/writing and processing using an ALU block. The results were
sent to a UART transmitter through an asynchronous FIFO to handle different clock rates and prevent
data loss.
- Designed RTL from scratch for system blocks including ALU, Register File, Synchronous FIFO, Integer
Clock Divider, Clock Gating, Synchronizers, Main Controller, UART TX, and UART RX.
- Verified functionality using a self-checking testbench.
- Constrained the system with synthesis TCL scripts and optimized the design using Design Compiler.
- Performed timing analysis and fixed setup and hold violations.
- Verified functionality equivalence using the Formality tool.
- Completed physical implementation and generated the GDS file through ASIC flow phases.
- Verified post-layout functionality, considering actual delays.
![pnr 1](https://github.com/user-attachments/assets/1d82b995-68f3-422b-a457-8346fa7f94c9)
![pnr](https://github.com/user-attachments/assets/88720c36-4e65-4a6d-8c1f-6fc517167d03)
![pnr 2](https://github.com/user-attachments/assets/00c71940-dcdd-44eb-9d1a-29026732b7bf)
