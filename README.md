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

![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/bd4a0b2c-cdbc-4184-ab08-81578f121e1f)

Figure -01 HALF ADDER

**Half Subtractor**

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed. 

Diff = A’B+AB’ =A ⊕ B
Borrow = A’B

 ![image](https://github.com/naavaneetha/HALF_ADDER_SUBTRACTOR/assets/154305477/d76b099c-513f-4e7c-843a-e2fd028a531a)

Figure -02 HALF Subtractor

**Truthtable**


Half Adder


<img width="412" height="322" alt="image" src="https://github.com/user-attachments/assets/845618f8-1972-44f2-8c1b-686cc2d1c336" />


Half Subtractor


<img width="415" height="316" alt="image" src="https://github.com/user-attachments/assets/5e3f5c57-925f-4fb7-b1f4-a83da952ace7" />

**Procedure**

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**Program:**

/* Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

1.Half Adder

<img width="1920" height="1080" alt="Screenshot 2025-11-23 211611" src="https://github.com/user-attachments/assets/7bcd0654-361d-4c3d-90bc-af45da9a9e1b" />


2.Half Subtractor

<img width="1920" height="1080" alt="Screenshot 2025-11-23 212413" src="https://github.com/user-attachments/assets/d4d9b511-819e-41d2-9666-34b5c2e51b3b" />


**RTL Schematic**


1.Half Adder


<img width="376" height="202" alt="Screenshot 2025-11-23 211716" src="https://github.com/user-attachments/assets/d1c130ea-b2e6-4f48-8690-852d5304de59" />


2.Half Subtractor


<img width="399" height="186" alt="Screenshot 2025-11-23 212153" src="https://github.com/user-attachments/assets/2fc598f7-9505-4366-b47a-8687c7e9dea4" />


**Output/TIMING Waveform**


1.Half Adder


<img width="1920" height="1080" alt="Screenshot 2025-11-23 212003" src="https://github.com/user-attachments/assets/996046a8-bd7c-48f6-a236-3656529598f4" />


2.Half Subtractor


<img width="1920" height="1080" alt="Screenshot 2025-11-23 212348" src="https://github.com/user-attachments/assets/d9ffaedd-6a57-4713-9fe9-b785c272db18" />

**Result:**

 Thus the half adder and half subtractor circuits were successfully designed, and their truth tables were verified in Quartus using Verilog programming.

