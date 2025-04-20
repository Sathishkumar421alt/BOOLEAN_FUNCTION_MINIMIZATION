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
 module funct1(a,b,c,d,f1);
 input a,b,c,d;
 output f1;
 assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
 endmodule
```
 

Developed by: RegisterNumber:*/SATHISH KUMAR.T/212224100053`



**RTL realization**

**Output:**

**RTL**
![Screenshot 2025-04-20 203429](https://github.com/user-attachments/assets/398595d6-ecb0-45ef-897d-1501940f4eaa)


**Timing Diagram**
![Screenshot 2025-04-20 203602](https://github.com/user-attachments/assets/78c29a50-38ab-47ca-8d9b-773ded6b02bb)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

