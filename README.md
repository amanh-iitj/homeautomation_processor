# Digital Home Automation Processor


## General Block Diagram Description

![Screenshot 2024-12-01 211832](https://github.com/user-attachments/assets/e9cc11b4-dfd2-4383-8084-161bb1bdb857)



- The Digital Home Automation Processor operates as follows:

### a) Input Instruction Registers:
- Five 32-bit input registers store control instructions.

### b) Input Control Logic:
- A program counter sequentially selects input instructions.
- The selected instruction is passed to a 32-bit register.

### c) Comparator:
- The instruction is compared against threshold values.

  
### d) Output Control Logic:
- Based on comparator results, two outputs are generated:
- 16-bit Intensity Change Instruction: Adjusts lighting brightness.
- 16-bit Color Change Instruction: Modifies the color of the lighting.
- This pipeline-like architecture ensures efficient processing and reliable control of home lighting systems.


## Simulation and Results

### Elaborated Design

![Screenshot 2024-12-01 212327](https://github.com/user-attachments/assets/ec3bc050-bcac-4360-ab71-f73f595198f1)


### Output Waveform

![Screenshot 2024-12-01 172741](https://github.com/user-attachments/assets/3a336b4d-e547-4b72-8e09-9f0376c1c4b4)


### Synthesized Design

![Screenshot 2024-12-01 212356](https://github.com/user-attachments/assets/3c8d59be-bb75-4ffe-b449-ec4e175f7da6)

![Screenshot 2024-12-01 212411](https://github.com/user-attachments/assets/49284b1d-011c-4aa5-94ff-b2a446a749ee)

![Screenshot 2024-12-01 212424](https://github.com/user-attachments/assets/21cd3968-e218-4133-90d8-8613b2b5038b)

![Screenshot 2024-12-01 212436](https://github.com/user-attachments/assets/f575b295-95ea-4a71-9d72-4c054d50b041)
