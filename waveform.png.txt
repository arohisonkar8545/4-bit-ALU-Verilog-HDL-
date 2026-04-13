4-Bit ALU using Verilog HDL 

 1. Title
Design and Implementation of 4-bit Arithmetic Logic Unit (ALU) using Verilog HDL

2. Objective
To design and simulate a 4-bit ALU using Verilog HDL that performs arithmetic and logical operations based on control signals and verifies results using waveform simulation.

 3. Introduction
An Arithmetic Logic Unit (ALU) is a key component of digital systems and processors. It performs arithmetic operations like addition and subtraction, and logical operations like AND, OR, and XOR. In this project, a 4-bit ALU is implemented using Verilog HDL and verified through simulation.

 4. Project Description
The ALU takes two 4-bit inputs and a control signal to perform different operations.

🔹 Operations:
Addition
Subtraction
AND
OR
XOR
🔹 Inputs:
A (4-bit)
B (4-bit)
Control signal (select operation)
🔹 Output:
4-bit result 

5. Flowchart of ALU Operation
        START
          |
          v
   Input A and B (4-bit)
          |
          v
   Select Control Signal
          |
          v
  -------------------------
  |        |        |     |
 ADD     SUB      AND    OR/XOR
  |        |        |     |
  -------------------------
          |
          v
     Generate Output
          |
          v
        END

 6. Design Methodology
ALU module designed using Verilog HDL
Testbench created for input verification
Simulation performed using EDA Playground
Output verified using waveform analysis

 7. Tools Used
Verilog HDL
EDA Playground 

8. Simulation & Waveform Analysis
The ALU was simulated successfully. The waveform confirms correct outputs for all operations based on control signals.


 9. Result
The 4-bit ALU was successfully designed, simulated, and verified. All operations produced correct outputs.

 10. Conclusion
This project demonstrates the implementation of a 4-bit ALU using Verilog HDL. It helps understand digital logic design, combinational circuits, and hardware simulation.

 11. Future Scope
Extension to 8-bit / 16-bit ALU
Addition of shift/rotate operations
Integration into CPU architecture
