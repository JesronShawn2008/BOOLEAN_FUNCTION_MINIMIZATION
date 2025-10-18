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

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

module funct1(a,b,c,d,f1); 

input a,b,c,d; 

output f1; 

assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 

endmodule ii) module funct2(w,x,y,z,f2); 

input w,x,y,z; 

output f2; 

assign f2=((~y & z)|( w & y )|(x & y)); 

endmodule

Developed by: RegisterNumber:*/ 25012933


**RTL realization**

<img width="688" height="761" alt="Screenshot Capture - 2025-10-18 - 23-24-04" src="https://github.com/user-attachments/assets/6cafac56-e010-40ff-a7da-5a6d73e400f5" />


**Output:**

**RTL**

**Timing Diagram**

<img width="709" height="675" alt="Screenshot Capture - 2025-10-18 - 23-25-07" src="https://github.com/user-attachments/assets/90095c5f-64af-49d4-89b9-7ce3c4b406b8" />

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

