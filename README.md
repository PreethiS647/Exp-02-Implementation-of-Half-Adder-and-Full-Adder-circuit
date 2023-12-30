Developed by: PREETHI S

RegisterNumber: 212223230157
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

*/
Logic symbol & Truthtable
RTL realization

### Half adder:
![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/6edd2f84-e4fc-4336-944f-50ba5efb8681)

### Full adder :
![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/5d64ebc1-f684-46c8-8702-b116c2a6ecbf)

### RTL
Half adder

![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/cf8df388-7095-4c8d-85a3-492b9b69fdaa)

Full adder
![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/1d599e5d-8a57-4b89-8670-4af18aa8557a)

### TIMING DIAGRAM


### TRUTH TABLE 
Half aader
![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/7bc944f7-315e-4949-9e3f-c2284138f951)
Full adder

![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/2f212be2-ebbe-4459-9963-7ae254168df6)
### Output:
Half adder
![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/0e72adfa-f63f-4b56-b36c-6e213fe9b169)
Full adder
![image](https://github.com/PreethiS647/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147313372/9f6876c0-fc7f-48f2-bd99-530955fa85ad)

### Result:
To design a half adder and full adder circuit and verify its truth table in Quartus using Verilog programming.
