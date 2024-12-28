
 NAME:S.ASWIN ANTONY

 REG NO:24001423

# EXP NO:4FULL ADDER AND SUBTRACTOR

Implementation-of-Full-Adder-and-Full-subtractor-circuit

# AIM:

To design a Full Adder and Full Subtractor circuit and verify its truth table in Quartus using Verilog programming.

# EQUIPMENTS REQUIRED:
Hardware – PCs, Cyclone II , USB flasher

Software – Quartus prime

# Full Adder and Full Subtractor

# FULLADDER:

Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin 

Carry = AB + ACin + BCin

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/0f30ba51-5ffb-4198-845f-18e054f675e7)

Figure -1 FULL ADDER

# Full Subtractor

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow.

![image](https://github.com/naavaneetha/FULL_ADDER_SUBTRACTOR/assets/154305477/02b24f51-ab51-4304-9ad6-7b81ffc1ead5)

Diff = A ⊕ B ⊕ Bin 

Borrow out = A'Bin + A'B + BBin

# TRUTH TABLE:
![Screenshot 2024-12-08 201124](https://github.com/user-attachments/assets/a3f8fd43-2f4e-49bf-83d3-ccb20f92f04f)


# PROCEDURE:

1. Type the program in Quartus software.

2. Compile and run the program.

3. Generate the RTL schematic and save the logic diagram.

4. Create nodes for inputs and outputs to generate the timing diagram.

5. For different input combinations generate the timing diagram
   

# PROGRAM:

FULL ADDER:

![Screenshot 2024-12-08 202704](https://github.com/user-attachments/assets/82c3f714-e1b0-46f7-b2ed-89fe0b22eab0)

FULL SUBTRACTOR:

![Screenshot 2024-12-08 203019](https://github.com/user-attachments/assets/9ea14411-48b4-489c-a3ab-48a201fed9e9)


# RTL OUTPUT:

FULL ADDER:

![Screenshot 2024-12-08 201219](https://github.com/user-attachments/assets/4155685d-b18c-4b72-b841-3c18b715ffc2)

FULL SUBTRACTROR:

![Screenshot 2024-12-08 201237](https://github.com/user-attachments/assets/99061a54-1d9e-4c5c-97b4-718d39dd6123)

# OUTPUT WAVEFORM:

![Screenshot 2024-12-08 201252](https://github.com/user-attachments/assets/5fa05354-0796-4628-bdf9-9669f9e493a4)

# RESULT:

Thus the Full Adder and Full Subtractor circuits are designed and the truth tables is verified using Quartus software.



