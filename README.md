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
![logic 1](https://github.com/user-attachments/assets/c3f37211-0042-4b51-970f-183e660460a8)


![logic 2](https://github.com/user-attachments/assets/623cce64-3998-41ae-aeb2-459633dc4b23)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber: 24900162*/

module funct1(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b&~c)|(~a&b&d)|(a&b&~c));

endmodule


module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule


**RTL realization**

**Output:**

**RTL**


**Timing Diagram**
![wavefoem 1](https://github.com/user-attachments/assets/acc21965-d195-4f2d-a540-0f675ecd6d48)

![waveform 2](https://github.com/user-attachments/assets/2f3bc9d2-b31d-4595-8545-46ae6162f38f)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

