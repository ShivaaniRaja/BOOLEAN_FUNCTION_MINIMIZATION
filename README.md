# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

Theory Boolean Algebra is a branch of algebra that deals with boolean values—true and false. It is fundamental to digital logic design and computer science, providing a mathematical framework for describing logical operations and expressions

**Logic Diagram**

![image](https://github.com/user-attachments/assets/1dae9352-713b-4e24-b522-4cfd94ccd8c8)

![image](https://github.com/user-attachments/assets/9a88ab12-df2f-49cf-82f7-08554b6be33a)

![image](https://github.com/user-attachments/assets/7f5384d2-4e04-47d9-99f1-5a33bbe4c366)

![image](https://github.com/user-attachments/assets/37c5bb69-294b-41b6-b29e-5dc991e56306)

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: RegisterNumber:24007075

Name:Shivaani.R

F1:

module exp2(a,b,c,d,f1);

input a,b,c,d;

output f1;

assign f1=((~b&~d)|(~a&b&d)|(a&b&~c));

endmodule

F2:

module exp2b(w,x,y,z,f2);

input w,x,y,z;

output f2;

assign f2=((~y&z)|(w&y)|(x&y));

endmodule


**RTL exp2**

![image](https://github.com/user-attachments/assets/a6631fb5-51fb-4117-919d-8c4525cc5afa)


**RTL exp2b**

![image](https://github.com/user-attachments/assets/b651cdd5-4198-4754-b338-7bb2bc029447)


**Timing Diagram**

exp2

![image](https://github.com/user-attachments/assets/4fd4962d-4a53-4315-811c-dd102d894bde)

exp2b

![image](https://github.com/user-attachments/assets/faff97d0-f539-4263-9c0b-9984ca957dc5)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.


