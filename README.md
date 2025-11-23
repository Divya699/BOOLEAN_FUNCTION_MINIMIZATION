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
```


* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:DIVYA PRIYA.S 
RegisterNumber:25018016



module funct2(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y & z)|( w & y )|(x & y));

endmodule

**RTL realization**
<img width="1907" height="974" alt="Screenshot 2025-11-23 214239" src="https://github.com/user-attachments/assets/ba24e913-dcfa-4d3d-8fd7-72abdc4e122f" />
<img width="1635" height="930" alt="Screenshot 2025-11-23 220448" src="https://github.com/user-attachments/assets/6c38fac4-a663-4fe8-97e6-9442a4e6b45d" />





**RTL**

**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

