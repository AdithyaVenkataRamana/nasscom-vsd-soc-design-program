# nasscom-vsd-soc-design-program

**Theory**



This project focuses on the integration of a standard cell design with the PicoRV32, a RISC-V CPU core using the SkyWater PDK (Process Design Kit). The PicoRV32 is a compact processor that uses the RISC-V instruction set, an open standard for efficient CPU design. Our goal is to integrate this CPU core into the chip design, connecting input/output (I/O) pads, general-purpose input/output (GPIO) pins, and power lines for appropriate use Design Following the Skywater PDK guidelines will do, providing open-source resources for building the chip.

![Screenshot 2024-10-15 205811](https://github.com/user-attachments/assets/c9d3c1bc-4360-44bf-b1a7-f946bc402763)


A die is like a tiny computer part that holds the circuits of a chip. Inside the core area, there are different sections where the chip's components are placed. Around this core, there are input/output (I/O) pads that help the chip communicate with other devices. This area doesn't have any actual logic circuits.
IPs are special, pre-designed parts that perform specific functions within the chip. They are like building blocks that were designed with a lot of thought and effort.


**The below given picture represents the processes and resources required for Digital ASIC Design**



![Screenshot 2024-10-15 212216](https://github.com/user-attachments/assets/5dc186f5-9bab-4d31-8f33-2728b9f778c6)


EDA Tools: These are software programs used to design and simulate the ASIC.
RTL (Register Transfer Level) Designs: The initial descriptions of the ASIC's functionality.
PDK (Process Design Kit): This contains information about the manufacturing process used to create the ASIC.
Open-Source Resources: These are websites and repositories that provide free and open-source tools, designs, and information for ASIC design.











**LABS:**


**Day1:**

1.Openlane is opened and design preparation is started

![1](https://github.com/user-attachments/assets/b9c46549-d30f-49c3-9460-2d9f99d64e68)


2.Synthesis operation in Openlane
![2](https://github.com/user-attachments/assets/0b20d3cd-b600-4bde-9afd-15fa30a31756)


3.Number of Cells Synthesised:
![3](https://github.com/user-attachments/assets/4351a96e-b17b-46da-9998-deb0d67b6b32)


Number of cells = 14876

4.Number of D Flip Flops:
![4](https://github.com/user-attachments/assets/efedea68-919c-4762-aad8-d487b871e6b5)


Number of D Flip Flops = 1613

5. Flop ratio = Number of D Flip Flops / Total Number of Cells Synthesised.
FR=0.1084296853993009
Percentage of D Flip Flop = 0.1084296853993009*100 = 10.84296853993009.
