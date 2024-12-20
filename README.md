**NAME**

SANDEEP S (24900896)

**REG NO:24900896**

# FULL_ADDER_SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

**AIM:**

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

**Full Adder and Full Subtractor**

**Full Adder**

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

**Figure -1 FULL ADDER**

**Full Subtractor**

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

**Truthtable**

![image](https://github.com/user-attachments/assets/b77cb901-189e-4c11-b0b1-5cf218b8beb6)
![image](https://github.com/user-attachments/assets/496c0d38-15f8-4c22-96d0-a807cfdcf8d2)


**Procedure**

Write the detailed procedure here 1 Type the program in Quartus software. 2
Compile and run the program. 3 Generate the RTL schematic and save the logic
diagram. 4 Create nodes for inputs and outputs to generate the timing diagram. 5 For
different input combinations generate the timing diagram

**Program:**

![image](https://github.com/user-attachments/assets/f0146587-af13-42aa-a8b6-23172e1049e5)

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/

**RTL Schematic**

![image](https://github.com/user-attachments/assets/9c9e1584-f823-476e-9e3a-3f96ec1344fc)


**Output Timing Waveform**

![image](https://github.com/user-attachments/assets/ecbcf691-d6c2-4728-8223-3904f8efb23f)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



