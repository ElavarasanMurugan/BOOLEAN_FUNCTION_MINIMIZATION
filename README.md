# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**
![Experiment 2 logic diagram ](https://github.com/user-attachments/assets/16a827cb-20fe-4d37-b6f9-b636b9ab3f2f)

![experiment 2 funct 2 logic diagram](https://github.com/user-attachments/assets/1e13a05a-c219-4d3a-8ee8-4df4f27d887d)


**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:*/
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule

**RTL realization**

**Output:**

**RTL**
![Experiment 2 waveform](https://github.com/user-attachments/assets/df865574-b292-4fd3-ac9a-30b8033d77bb)

![experiment 2 funct 2 waveform ](https://github.com/user-attachments/assets/aeb86e93-2741-4ab8-9b36-be8bd183f38c)

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

