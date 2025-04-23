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

Developed by: Rihan Ahamed.S RegisterNumber:212224040276*/
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
![image](https://github.com/user-attachments/assets/c4f636bb-90ce-4f99-8e60-4fce29944309)
![image](https://github.com/user-attachments/assets/ec1e87f0-e090-4f30-90ae-42438d8df1e2)

**Timing Diagram**
![image](https://github.com/user-attachments/assets/96b06ce8-fbce-415c-b461-fa1b9548d870)
![image](https://github.com/user-attachments/assets/48661742-bd1a-4785-9c75-82d8e322563b)


**Result:**
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

