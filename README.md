## NAME:MANIMARAN
## REGISTER NO:24008541
# EXP 1:IMPLEMENTATION OF STUDY OF BASIS GATES

# AIM: 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

# EQUIPMENTS REQUIRED:

Software – Quartus prime 

# THEORY

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

# AND GATE

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

# OR GATE

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

# NOT GATE

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

# NAND GATE

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

# NOR GATE

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

# EX-OR GATE

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

# EX-NOR GATE

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

# PROCEDURE

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


# PROGRAM
module logicgates (a,b,notgate,andgate,orgate,nandgate,norgate,xorgate,xnorgate);
input a,b;
output notgate,andgate,orgate,nandgate,xorgate,xnorgate,norgate;
not(notgate,a);
and(andgate,a,b);
or(orgate,a,b);
nand(nandgate,a,b);
nor(norgate,a,b);
xor(xorgate,a,b);
xnor(xnorgate,a,b);
endmodule

# LOGIC SYMBOL & TRUTH TABLE
![WhatsApp Image 2024-10-28 at 11 29 36_6654bb94](https://github.com/user-attachments/assets/20c5f0a5-3460-4847-8b13-1a1f1ac41eae)

# RTL OUTPUT:
![Screenshot (47)](https://github.com/user-attachments/assets/509b8ac0-9bc1-489d-85c7-2ca37d38e8a6)

# OUTPUT WAVEFORM 
![Screenshot (50)](https://github.com/user-attachments/assets/c852e837-6af4-4cbf-9eb3-0bcef264243d)

# RESULT:
To study and verify the truth table of logic gates in Quartus II using Verilog programming

