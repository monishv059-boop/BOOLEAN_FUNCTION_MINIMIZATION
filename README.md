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
~~~
module ex2(a,b,c,d,f1,w,x,y,z,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1=((~b&~d)| (~a&b&d)| (a&b&~c));
assign f2=((~y&z)|(x&y)|(w&y));
endmodule
~~~

Developed by:MONISH V
RegisterNumber:*212225220066


**RTL realization**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1df57a96-bead-4f32-a2e8-5e406f6eed26" />

**Output:**
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22a2d9c7-4a83-4324-8edf-02f25d5f6287" />


**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


