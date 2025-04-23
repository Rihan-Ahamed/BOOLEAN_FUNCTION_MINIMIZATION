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

Developed by:Rihan Ahamed.S RegisterNumber:212224040276
~~~
module func(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule

module func1(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y&z)|(w&y)|(x&y));
endmodule
~~~



**RTL realization**

**Output:**

**RTL**
![image](https://github.com/user-attachments/assets/713e42b0-dec8-4a12-ae86-2c83edd3866d)
![image](https://github.com/user-attachments/assets/b351ffb1-8472-40c7-8af2-74256c963760)


**Timing Diagram**
![image](https://github.com/user-attachments/assets/d74a5564-3b15-45a3-b656-c22dea02a8d4)
![image](https://github.com/user-attachments/assets/9789d1e9-98f3-4450-92aa-9057fe399e7c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

