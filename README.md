# BOOLEAN_FUNCTION_MINIMIZATION

**AIM:**

To implement the given logic function verify its operation in Quartus using Verilog programming.

F1= A’B’C’D’+AC’D’+B’CD’+A’BCD+BC’D 

F2=xy’z+x’y’z+w’xy+wx’y+wxy

**Equipment Required:**

Hardware – PCs, Cyclone II , USB flasher

**Software – Quartus prime**
![382731654-7937c32c-6c5b-4be0-bf28-d48d2af093a1](https://github.com/user-attachments/assets/9daac366-6bc1-496a-9882-27d0d4c43f3f)

**Theory**

**Logic Diagram**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**
module exp2-1(a,b,c,d,f1); input a,b,cd; output f1; assign f1=((~B&~D)|(~A&B&D)|(A&B&~C)); endmodule module exp2-2(w,x,y,z,f2); input w,x,y,z; output f2; assign f2=((~y&z)|(x&y)|(w&y)); endmodule /* Program to implement the given logic function and to verify its operations in quartus using Verilog programming.

Developed by: RegisterNumber:*/24007963


**RTL realization**
![382730162-95bb2340-574f-41a7-b427-548a1ba24d6a](https://github.com/user-attachments/assets/758e7abd-c561-4563-b9ba-5e242c42ebd0)
![382731124-6cbb5afe-2e54-4d6f-ba57-850922302fa0](https://github.com/user-attachments/assets/8abc5343-7dd6-4273-b4cf-f2bcddd24fc5)

**Timing Diagram**
![382731363-319ed8da-1018-![382731257-ffe6d8e8-58a1-4929-b0af-206e67a98e0e](https://github.com/user-attachments/assets/31278568-f87e-4ae2-95be-cb4d5a44f722)
4745-83d7-28b7189ae155](https://github.com/user-attachments/assets/f6acd1a2-ea98-420a-8ce2-128758d6d43c)

**Result:**

Thus the given logic functions are implemented using and their operations are verified using Verilog programming.

