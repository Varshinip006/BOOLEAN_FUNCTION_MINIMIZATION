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
```
module logic function(a,b,c,d,f1);
input a,b,c,d;
output f1;
assign f1=((~b &~d)|(~a & b & d)|(a & b & ~c));
endmodule

module logic function(w,x,y,z,f2);
input w,x,y,z;
output f2;
assign f2=((~y & z)|(w & y)|(x & y));
endmodule

Developed by:Priya Varshini P
RegisterNumber:212224240119
Date: 12.03.2025

```

**RTL realization**

 ![Screenshot 2025-03-18 113009](https://github.com/user-attachments/assets/76f2caa2-8692-4006-8a21-8624d5fad9bd)
 
![Screenshot 2025-03-18 114150](https://github.com/user-attachments/assets/e8d47816-1fd5-4050-9411-0b4c1cea78c5)


**Output:**

![Screenshot 2025-03-18 113627](https://github.com/user-attachments/assets/e04564a6-4cee-4402-91a5-d14404bf9a9c)

![Screenshot 2025-03-18 114421](https://github.com/user-attachments/assets/2bda14d4-a3a1-4dd0-84a4-02078e1d481e)


**RTL**


**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

