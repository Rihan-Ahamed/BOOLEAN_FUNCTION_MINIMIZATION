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

 Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by:Rihan Ahamed.S RegisterNumber: 212224040276
~~~
module Boolean(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c));
assign f2=((~y & z)|( w & y )|(x & y));
endmodule
~~~


**RTL realization**

**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/13b89606-05b3-4101-8b3b-57e0ff126b1d)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/c6fbf2fe-12f3-427b-9929-944245b6a661)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

