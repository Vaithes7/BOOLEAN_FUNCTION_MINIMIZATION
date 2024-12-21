# BOOLEAN_FUNCTION_MINIMIZATION

**DATE:** 05.10.2024

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**

**Theory**

**Logic Diagram**

![Screenshot (26)](https://github.com/user-attachments/assets/b85951fc-457d-43d7-a406-a19ddff6b4c3)
![Screenshot (34)](https://github.com/user-attachments/assets/b8fe0e4f-e8f5-48de-aa82-0d342fcc9c65)



**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
```
module func1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule

```
```
module funct1(a,b,c,d,f1); 
input a,b,c,d; 
output f1; 
assign f1=((~b & ~d)|(~a & b & d)|(a & b & ~c)); 
endmodule

```


/* Program to implement the given logic function and to verify its operations in quartus using Verilog programming. 

Developed by: Vaitheswaran N RegisterNumber: 24901212*/


**RTL realization**

**Output:**

**RTL**

 ![Screenshot (27)](https://github.com/user-attachments/assets/ea0222f7-2e75-4459-8b6b-44a0925b507a)
 ![Screenshot 2024-12-01 191304](https://github.com/user-attachments/assets/8dea6029-95bf-433d-911f-0839715b4583)




**Timing Diagram**

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

