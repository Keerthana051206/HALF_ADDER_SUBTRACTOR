# HALF_ADDER_SUBTRACTOR

Implementation-of-Half-Adder-and-Half Subtractor-circuit

**AIM:**

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

**Equipments Required:**

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

**Half Adder**

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB
<img width="341" alt="image" src="https://github.com/user-attachments/assets/73cf84ec-25fa-4d3c-a35f-db30a9bcb433" />



Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B
<img width="390" alt="image" src="https://github.com/user-attachments/assets/5abc78aa-6fb4-4555-8e6c-a681fafb295a" />


Figure -02 HALF Subtractor

**Truthtable**

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by: KEERTHANA C RegisterNumber:*/ 212224220047
<img width="433" alt="image" src="https://github.com/user-attachments/assets/e89b72e6-35d7-4fc7-a9c7-2522973dbcbf" />


**RTL Schematic**
<img width="326" alt="image" src="https://github.com/user-attachments/assets/e125cbe1-59cc-4d5f-9f98-a06355410410" />

<img width="276" alt="image" src="https://github.com/user-attachments/assets/6df70bea-dad7-4fb6-8c86-0f37296ba726" />


**Output/TIMING Waveform**
<img width="470" alt="image" src="https://github.com/user-attachments/assets/66d5fc67-62eb-41bb-8079-32ce0a80c1b2" />


**Result:**
Design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming is verified.
