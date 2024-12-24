# Design Of Digital Home Automation Processor


- The Digital Home Automation Processor operates as follows:

### a) Input Instruction Registers:
- Four 32-bit input registers store control instructions.

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

![Screenshot 2024-12-24 222840](https://github.com/user-attachments/assets/6b28a48a-3a84-4561-96bd-73d9d384d0c9)



### Output Waveform

![Screenshot 2024-12-24 222813](https://github.com/user-attachments/assets/9d645609-fed5-48f4-b4bb-7c9c6eabbd49)





### Synthesized Schematic

![Screenshot 2024-12-24 222948](https://github.com/user-attachments/assets/3290eeb4-ecee-4499-8a67-896408ef46b5)

![Screenshot 2024-12-24 223000](https://github.com/user-attachments/assets/1efe7e14-53dc-4ef1-bcb6-baccfa7277c6)

![Screenshot 2024-12-24 223019](https://github.com/user-attachments/assets/8a632ee0-6c5d-4bd7-8483-cb969241fede)




### Synthesized Design

![Screenshot 2024-12-24 222859](https://github.com/user-attachments/assets/0f943113-7ecc-49bc-871c-24ebc59980e7)

![Screenshot 2024-12-24 222915](https://github.com/user-attachments/assets/ed57df09-8a7b-4a9c-8a66-fac7bf280d38)

![Screenshot 2024-12-24 222935](https://github.com/user-attachments/assets/2fc479a8-749f-4c3d-aaac-caa737277491)


### Power Report


![Screenshot 2024-12-24 223035](https://github.com/user-attachments/assets/582149f1-1f7a-4732-a06f-26070541b696)

