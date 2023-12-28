# Experiment-04-Half-Subtractor-and-Full-subtractor
## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To design a half subtractor and full subtractor circuit and verify its truth table in Quartus using Verilog programming.

## Equipments Required:

Hardware – PCs, Cyclone II , USB flasher
Software – Quartus prime

## Theory :
Subtractor circuits take two binary numbers as input and subtract one binary number input from the other binary number input. Similar to adders, it gives out two outputs, difference and borrow (carry-in the case of Adder). There are two types of subtractors.

## Half Subtractor Full Subtractor
## Half Subtractor :

The half-subtractor is a combinational circuit which is used to perform subtraction of two bits. It has two inputs, X (minuend) and Y (subtrahend) and two outputs D (difference) and B (borrow). To perform x - y, we have to check the relative magnitudes of x and y. If x ;;, y, we have three possibilities: 0 - 0 = 0, 1 - 0 = 1, and 1 - I = 0. The result is called the difference bit. If x < y, we have 0 - I, and it is necessary to borrow a 1 from the next higher stage. The I borrowed from the next higher stage adds 2 to the minuend bit, just as in the decimal system a borrow adds 10 to a minuend digit. With the minuend equal to 2, the difference becomes 2 - I = 1. The half-subtractor needs two outputs. One output generates the difference and will be designated by the symbol D. The second output, designated B for borrow, generates the binary signal that informs the next stage that a I has been borrowed.
![half-subtractor9](https://user-images.githubusercontent.com/36288975/166112538-58c3bc7c-ee5d-4e6a-ac8d-8e8328efe27a.png)


Sum = X'Y+XY' = X ⊕ Y
Carry=X'Y

## Full Subtractor :

A full subtractor is a combinational circuit that performs subtraction involving three bits, namely minuend, subtrahend, and borrow-in . It accepts three inputs: minuend, subtrahend and a borrow bit and it produces two outputs: difference and borrow. 
![full-subtractor6](https://user-images.githubusercontent.com/36288975/166112541-24c68359-3de8-4674-ae22-8272ffc385ed.png)


Diff = A ⊕ B ⊕ Bin B = A'Bin + A'B + BBin

## Procedure

STEP 1: Use module project name(input,output) to start the Verilog programmming.
STEP 2: Assign inputs and outputs using the word input and output respectively.
STEP 3: Use defined keywords like wire,assign and required logic gates to represent the boolean
expression.
STEP 4: Use each output to represnt onre for differnce and the other for borrow.
STEP 5: End the verilog program using keyword endmodule.

## Program:
Developed by : K Vijay

RegisterNumber : 23004034 

## Code :
## Half Subtractor :

![Exp4 hs code](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/56608117-12d0-488e-8b3e-959d813efd4e)

## Full Subtractor :

![Exp4 fs code](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/07107881-4dae-4046-8acf-b7284b06ab77)

## Output:
## Truthtable:
## HAlf Subtractor:

![Exp4 truthtable hs](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/a014b327-ed08-4121-9e56-853144fa07f6)

## Full Subtractor:

![Exp4 truthtable fs](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/8a3e5c79-e15f-499a-be4f-a54936fa8df9)


##  RTL realization:
## Half subtractor:

![Exp4 hs RTL diagram](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/d7b3ddd1-d451-4259-ab0a-e43f19dd4838)

## Full Subtractor:

![Exp4 fs RTL diagram](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/7f84aa86-fc21-4173-98fc-d432d4494986)


## Timing diagram :
## Half Subtarctor:

![hs wave](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/f998c602-f138-4fec-9e4c-b5e3dedb325b)

## Full Subtractor:

![fs wave](https://github.com/vijaygowdu/Experiment--03-Half-Subtractor-and-Full-subtractor/assets/147473788/324ff7f3-8521-4f01-8491-1e65c086fc2f)


## Result:
Thus the half subtractor and full subtractor circuits are designed and the truth tables is verified using quartus software.
