# Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit

# Implementation-of-Half-Adder-and-Full-Adder-circuit
### AIM:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.

### Equipments Required:
Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime
Theory
Adders are digital circuits that carry out addition of numbers.

### Half Adder
Half adder is a combinational circuit that performs simple addition of two binary numbers. The input variables designate the augend and addend bits; the output variables produce the sum and carry. It is necessary to specify two output variables because the result may consist of two binary digits.

Sum = A’B+AB’ =A ⊕ B Carry = AB

### Full Adder
Full adder is a digital circuit used to calculate the sum of three binary bits. It consists of three inputs and two outputs. Two of the input variables, denoted by A and B, represent the two significant bits to be added. The third input, Cin, represents the carry from the previous lower significant position. Two outputs are necessary because the arithmetic sum of three binary digits ranges in value from 0 to 3, and binary 2 or 3 needs two digits. The two outputs are sum and carry.

Sum =A’B’Cin + A’BCin’ + ABCin + AB’Cin’ = A ⊕ B ⊕ Cin Carry = AB + ACin + BCin

 ![image](https://user-images.githubusercontent.com/36288975/163552156-a13e5a56-c638-4110-97d9-8896907c8d25.png)

#### Figure -01 HALF ADDER 


![image](https://user-images.githubusercontent.com/36288975/163552057-b3547877-6d07-45b4-b7e0-bcfebfad9e1d.png)

#### Figure -02 FULL ADDER 

### Procedure

Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
### 
Program:

Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.

Developed by : KEERTHIVASAN S

Register Number : 23002436

Code : 

Half Adder :

![Exp3 ha code](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/1f5b70d1-93c7-40e4-888c-2ed8e08a01cd)

Full Adder :

![Exp3 fa code](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/bab483c3-293b-4c9f-b141-b4de63008edd)

Truthtable : 

Half Adder :

![Exp3 truthtable (ha)](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/411a7115-956c-4662-9204-b8c37d3fab96)

Full Adder :

![Exp3 truthtable (fa)](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/1d1cf8a8-f914-4673-9c53-c390f08382cd)

RTL Diagram :

Half Adder :

![Exp3 ha RTL diagram](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/af4aaccc-62f4-4af6-bba0-7b27912ac528)

Full Adder :

![Exp3 fa RTL diagram](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/96fb2937-9a09-42e5-b0b5-b5f86fb8752e)

Output :

Half Adder :

![Exp3 ha wave](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/5596e724-ff5b-4d37-b56f-a8277c8c956d)

Full Adder :

![Exp3 fa wave](https://github.com/ikeerthivasanswaminathan/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/148937372/63481b25-e3e9-42ce-b343-28a0615ded0d)

### Result : 
Thus the half adder and full adder circuit are designed and the truth table for half adder and full adder are verified.
