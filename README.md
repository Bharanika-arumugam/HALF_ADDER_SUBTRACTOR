### NAME:BHARANIKA.A.S
### REG NO:24901181
### EXPERIMENT3: HALF ADDER SUBTRACTOR


# AIM

To design a half adder and half subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED

Hardware – PCs, Cyclone II , USB flasher 

Software – Quartus prime Theory Adders are digital circuits that carry out the addition of numbers.

# HALF ADDER

Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

# HALF SUBTRACTOR
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

# TRUTH TABLE
![EXP3 tt](https://github.com/user-attachments/assets/c2ea65a3-42c6-4741-aa6c-380763eae44e)

# PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM

![EXP3 PRG](https://github.com/user-attachments/assets/6f8fb0b6-fa7a-4775-be14-28b25f782b03)


# RTL OUTPUT
![EXP3 RTL](https://github.com/user-attachments/assets/acd281c5-8780-4cbc-a8ac-e59b2c5e0c37)

# OUTPUT WAVEFORM
![exp3 waveform](https://github.com/user-attachments/assets/41240329-2c6e-460b-ae14-ff1a3f8b390f)

# RESULT
Studied and verified the half adder and subtractor using verilog programming successfully.
