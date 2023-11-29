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

### Procedure :
```
Connect the supply (+5V) to the circuit
Switch ON the main switch
If the output is 1, then the led glows.
```
## Program:
```
Program to design a half adder and full adder circuit and verify its truth table in quartus using Verilog programming.
Developed by: Dharanish MS
RegisterNumber: 23011819
```
Logic symbol & Truthtable
RTL realization

# Code:
### HALF ADDER :


![code](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/84cf8f6e-db68-48d8-bff7-9e99c0c93914)


### FULL ADDER :


![code](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/e9446b4b-1c02-48e0-9190-6f4c5459c95a)

### RTL:

### HALF ADDER :


![logic diagram](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/003735ff-be27-4c9d-98b0-f0adb8e9dfe5)


### FULL ADDER :


![RTL](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/61340885-b354-475b-bfb6-6c74d05443b8)


### TIMING DIAGRAM:

### HALF ADDER :


![output](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/568c4a8b-170b-4e27-b323-2738a3fcead6)

### FULL ADDER :



![output](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/55781790-d25f-4a26-9312-df8dfabee01d)


### TRUTH TABLE :


### HALF ADDER :

![truth table](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/0bb12d18-fbd4-4a31-ac1b-59bed6844c6e)




### FULL ADDER :



![truth table](https://github.com/MSDharanish-23011819/Exp-02-Implementation-of-Half-Adder-and-Full-Adder-circuit/assets/147139454/b7234b71-18fa-4672-aac5-1baf5328dac5)




### Result:
Thus, the half adder amd full adder circuits are designed and the truth tables is verified using quartus software.


