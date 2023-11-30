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
/*
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.


Developed by: Hemavathy.S
RegisterNumber: 23013552 

Logic symbol & Truthtable
RTL realization

## Code:
## Half adder
![exp 3  halfadder](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/e730bf0a-05d7-41f0-909a-e9fda05c550f)
## Full adder
![exp 3 fulladder](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/bf738358-1734-4487-a311-120b8bc20567)

## Truth table:

![exp3 (2)](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/344696db-9c44-41bd-ad11-cd6a46a116bf)

## Diagram

## HALF ADDER

![HalfAdder](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/68cf92d1-7178-4bb0-a39b-ded4564283ad)

## FULL ADDER

![FullAdder](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/8859a00d-c9e6-4aa4-9c84-a99c8587e4b1)



### Output:

HALF ADDER

![exp3 halfadder](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/e1df388a-80e7-4f49-a966-380b3455190b)

FULL ADDER

![exp3 fulladder](https://github.com/Hemaatchu/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147328300/e4584069-9c99-4338-a158-9d91ec5ef906)


## Result:

Thus the half adder and full adder circuits are designed and the truth tables is verified using quartus software.
