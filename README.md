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
![image](https://github.com/user-attachments/assets/d22bcfab-81ea-446c-824f-9f38dded32e5)


**Procedure**

Write the detailed procedure here

**Program:**

/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming. Developed by: RegisterNumber:
*/
![image](https://github.com/user-attachments/assets/2cabdae6-5d34-430a-90a1-dc3c7d3bc28d)


**RTL Schematic**
![WhatsApp Image 2025-01-01 at 18 13 22_fd7c8a24](https://github.com/user-attachments/assets/278af9ce-603c-401f-9bb1-a4e8bda5dad3)

![WhatsApp Image 2025-01-01 at 18 13 34_f633e968](https://github.com/user-attachments/assets/470d0312-68f5-4dec-88c3-69df165e0408)

**Output Timing Waveform**
![WhatsApp Image 2025-01-01 at 18 13 47_23f07703](https://github.com/user-attachments/assets/1038e88b-8394-4d67-ac55-256bd28e3075)
![WhatsApp Image 2025-01-01 at 18 14 05_f01d28c0](https://github.com/user-attachments/assets/6c64cbdb-3987-48af-bfa3-52317b9c5eb1)


**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



