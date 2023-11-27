# Experiment--03-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor
The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor
A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a half subtractor and full subtractor circuit and verify its truth table in quartus using Verilog programming.

Developed by:   Nikeshkumar C

RegisterNumber:  23003997

Code:

Full Subtractor:

![Exp4 fs code](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/b9dd6f70-1907-4ed9-9227-74287765cde1)

Half Subtractor:

![Exp4 hs code](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/71eeed0c-e4e4-4036-a265-66c0cc50c1b1)


Truth Table:

Full Subtractor:

![Exp4 truthtable fs](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/716840a4-861d-47c8-b7c3-016718f4f56e)

Half Subtractor:

![Exp4 truthtable hs](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/2112b02a-acb2-4783-b04a-5ad2a38c722d)

RTL Diagram:

Full Subtractor:

![Exp4 fs RTL diagram](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/12229d49-cd2a-4066-b353-48c28231f173)

Half Subtractor:

![Exp4 hs RTL diagram](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/dbf81087-aa34-4e43-b5a8-0e9fff3889fd)

## Output:

Full Subtractor:


![Exp3 fs wave](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/15b37515-a076-4f81-8917-e5f636eef160)

Half Subtractor:


![Exp3 hs wave](https://github.com/nicknikesh/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/145633284/42af4361-f1f8-4679-9108-699c50997ad4)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
