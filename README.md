12/11/2024                                       S. Siddharth. Register number: 240002384

𝑬𝑿𝑷 1:𝑺𝒕𝒖𝒅𝒚 𝒐𝒇 𝒃𝒂𝒔𝒊𝒄 𝒅𝒊𝒈𝒊𝒕𝒂𝒍 𝑰𝑪’𝒔 𝒂𝒏𝒅 𝒗𝒆𝒓𝒊𝒇𝒊𝒄𝒂𝒕𝒊𝒐𝒏 𝒐𝒇 𝒕𝒓𝒖𝒕𝒉 𝒕𝒂𝒃𝒍𝒆𝒔 𝒇𝒐𝒓 𝒅𝒊𝒇𝒇𝒆𝒓𝒆𝒏𝒕 𝒍𝒐𝒈𝒊𝒄 𝒈𝒂𝒕𝒆𝒔, 𝒓𝒆𝒂𝒍𝒊𝒛𝒂𝒕𝒊𝒐𝒏 𝒖𝒔𝒊𝒏𝒈 𝑽𝒆𝒓𝒊𝒍𝒐𝒈
**AIM:** 

To study and verify the truth table of logic gates in Quartus II using Verilog programming.

**Equipments Required:**

Software – Quartus prime 

**Theory**

Introduction Logic gates are the basic building blocks of any digital system. Logic gates are electronic circuits having one or more than one input and only one output. The relationship between the input and the output is based on a certain logic. Based on this, logic gates are named as

AND gate OR gate NOT gate NAND gate NOR gate Ex-OR gate Ex-NOR gate

**AND gate**

The AND gate is an electronic circuit that gives a high output (1) only if all its inputs are high. A dot (.) is used to show the AND operation i.e. A.B or can be written as AB
Y= A.B

**OR gate** 

The OR gate is an electronic circuit that gives a high output (1) if one or more of its inputs are high. A plus (+) is used to show the OR operation.
Y= A+B

**NOT gate**

The NOT gate is an electronic circuit that produces an inverted version of the input at its output. It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A. This is also shown as A' or A with a bar over the top, as shown at the outputs.
Y= A'

**NAND gate**

This is a NOT-AND gate which is equal to an AND gate followed by a NOT gate. The outputs of all NAND gates are high if any of the inputs are low. The symbol is an AND gate with a small circle on the output. The small circle represents inversion.
Y= (AB)’

**NOR gate**

This is a NOT-OR gate which is equal to an OR gate followed by a NOT gate. The outputs of all NOR gates are low if any of the inputs are high. The symbol is an OR gate with a small circle on the output. The small circle represents inversion.
Y= (A+B)’

**Ex-OR gate**

The 'Exclusive-OR' gate is a circuit which will give a high output if either, but not both of its two inputs are high. An encircled plus sign (⊕) is used to show the Ex-OR operation.
Y= A⊕B

**Ex-NOR gate**

The 'Exclusive-NOR' gate circuit does the opposite to the EX-OR gate. It will give a low output if either, but not both of its two inputs are high. The symbol is an EX-OR gate with a small circle on the output. The small circle represents inversion.
Y= A⊕B

**Procedure** 

1.	Type the program in Quartus software.

2.	Compile and run the program.

3.	Generate the RTL schematic and save the logic diagram.

4.	Create nodes for inputs and outputs to generate the timing diagram.

5.	For different input combinations generate the timing diagram.


**PROGRAM**

Program for logic gates and verify its truth table in quartus using Verilog programming

 Developed by: RegisterNumber: 24002384

 AND 

Module ex1 (a,b,y) ;
Input a,b;
Output y ;
And g1 (y,a,b) ;
Endmodule
 
**Logic symbol & Truthtable**
![download](https://github.com/user-attachments/assets/7097ca7b-4f2a-4b46-b2cb-8f27042fc6e9)


**RTL realization Output:** 
![Screenshot 2024-11-12 103503](https://github.com/user-attachments/assets/266452fb-205e-40b6-8e9e-bed4eaefa32d)


**RTL**
![Screenshot 2024-11-12 104503](https://github.com/user-attachments/assets/1d917a81-ee87-4afa-bc49-a3d4c977e983)


**Result:** 
Hence the truth table of logic gates in Quartus II using Verilog programming is studied and verified.




