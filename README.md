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
  Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 
  Developed by:N.Naghul varshan
  RegisterNumber:24901302
 ```
```
module funct1(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
endmodule
```
**RTL realization**

![image](https://github.com/user-attachments/assets/d4dbd8a2-9818-437f-8317-f06c70fb0d44)

**Output:**

![Logic diagram](https://github.com/user-attachments/assets/0efbf9d9-12ca-4d23-955e-cced45104797)


**Timing Diagram**

![Waveform](https://github.com/user-attachments/assets/07e573ed-267d-4cdd-9aa0-a8d42c4cdc63)


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

