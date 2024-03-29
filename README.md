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

**FULL ADDER:**

![4 1](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/d4602f47-367b-49a7-a5c3-7d70cb3d4ec1)
 
 
**FULL SUBTRACTOR:**

![4 2](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/37d0c376-2243-43a3-9adf-91d5ff802610)

**Procedure**

Write the detailed procedure here

**Program:**
/* Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.
Developed by: VAISHNAVIDEVI V
RegisterNumber:212223040230
*/

**FULL ADDER:**

![4 3](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/edee3917-43f8-4180-94bf-6e5e97340c3d)



**FULL SUBTRACTOR:**


![4 4](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/7ca8edc2-5bf5-406d-ab48-5cea358ddef0)




**RTL Schematic**


**FULL ADDER:**


![4 5](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/9fce1d18-f774-46bc-b01b-664433871ad9)

**FULL SUBTRACTOR:**


![4 6](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/38e916f9-4f1d-4f27-a5cc-96a3c80bcc2f)


**Output Timing Waveform**

  ![4 7](https://github.com/vaishnavidevi23013992/FULL_ADDER_SUBTRACTOR/assets/151864235/ba9684c7-7245-401a-b722-3f626eaf69bf)

**Result:**

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



