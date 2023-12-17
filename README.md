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
Developed by: V RAKSHA DHARANIKA
RegisterNumber: 23013260

###CODE:



HALF ADDER:




![Exp3 ha code](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/82b503a3-2bc8-40a7-96d5-1991b65aa15d)



FULL ADDER:


![Exp3 fa code](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/11d571d9-f80b-4d0a-85f3-564095649f19)






###Truthtable:

HALF ADDER:



![Exp3 truthtable (ha)](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/d9120200-3d57-4f31-b3d0-6dee85d045d1)





FULL ADDER:


![Exp3 truthtable (fa)](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/ed48abbd-a52d-44ce-88d5-82d4532b1103)






### Output:


### RTL:


HALF ADDER:



![Exp3 ha RTL diagram](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/c480625b-7c65-4844-be9c-6c9cccd3afb8)





FULL ADDER:





![Exp3 fa RTL diagram](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/d6cdb826-9cfa-41ff-a15e-f00309e29e35)


### TIMING DIAGRAM:



HALF ADDER:




![exp3 ha wave](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/163c8a35-4b58-44bf-9285-9ac821be53eb)





FULL ADDER:





![exp 3 fa wave](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/625a4720-e8c8-417a-b146-21d86788dba6)



### TRUTH TABLE :




HALF ADDER:


![Exp3 truthtable (ha)](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/d9120200-3d57-4f31-b3d0-6dee85d045d1)




FULL ADDER:




![Exp3 truthtable (fa)](https://github.com/rakshadharanika/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/149348380/ed48abbd-a52d-44ce-88d5-82d4532b1103)





### Result:
