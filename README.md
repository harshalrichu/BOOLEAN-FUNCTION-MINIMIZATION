## BOOLEAN-FUNCTION-MINIMIZATION
## AIM
To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D

F2=xy’z+x’y’z+w’xy+wx’y+wxy

## Equipment Required:
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime
Theory
Logic Diagram
## Procedure
Type the program in Quartus software.

Compile and run the program.

Generate the RTL schematic and save the logic diagram.

Create nodes for inputs and outputs to generate the timing diagram.

For different input combinations generate the timing diagram.

## Program:
```

/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

module boolean(a,b,c,d,w,x,y,z,f1,f2);
input a,b,c,d,w,x,y,z;
output f1,f2;
assign f1 = ~b&~d | a&b&~c | ~a&b&d;
assign f2 = ~y&z | x&y | w&y;
```
##  Output:

<img width="431" height="362" alt="image" src="https://github.com/user-attachments/assets/b9725dde-4808-4cf3-8244-2a6fdbd897d6" />

<img width="827" height="157" alt="image" src="https://github.com/user-attachments/assets/b7be8d20-baa3-4b11-9273-2616cc174d02" />

## Result:
Thus the given logic functions are implemented using and their operations are verified using Verilog programming.
