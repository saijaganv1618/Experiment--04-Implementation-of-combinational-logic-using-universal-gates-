# Experiment--04-Implementation-of-combinational-logic-using-universal-gates-
 ## Implementation-of-Half-subtractor-and-Full-subtractor-circuit
## AIM:
To implement the given logic function using NAND and NOR gates and to verify its operation in Quartus using Verilog programming.
F=((C'.B.A)'(D'.C.A)'(C.B'.A)')' using NAND gate
F=(((C.B'.A)+(D.C'.A)+(C.B'.A))')' using NOR gate


## Equipments Required:
## Hardware – PCs, Cyclone II , USB flasher
## Software – Quartus prime
## Theory
 
 
 
 


## Procedure



Write the detailed procedure here 


## Program:
/*
Program to design a Implementation of combinational logic using universal gates-  and verify its truth table in quartus using Verilog programming.
Developed by: Jagan a
RegisterNumber:  212221230037
NOR GATE PROGRAM:
module nor1(a,b,c,d,f);
input a,b,c,d;
output f;
assign  f=(~(~((c&(~b)&a)|(d&(~c)&a)|(c&(~b)&a))));
endmodule

*/

## Output:

Truthtable
![tt 1](https://user-images.githubusercontent.com/59290560/167337830-7b60e738-3a8c-40d1-86bc-36a9ca9e59e8.png)




##  RTL realization
![rtl 1](https://user-images.githubusercontent.com/59290560/167337875-8893bb0d-ef7f-4877-a928-d252c8e8af5b.png)


## Timing diagram 
![td 1](https://user-images.githubusercontent.com/59290560/167337901-02e275c3-2c51-4bbd-ba0c-018d03a113e4.jpeg)






## Program:
/*
Program to design a Implementation of combinational logic using universal gates-  and verify its truth table in quartus using Verilog programming.
Developed by: Jagan a
RegisterNumber:  212221230037
NAND GATE PROGRAM:

module un1(a,b,c,d,f);
input a,b,c,d;
output f;
assign  f=((~(~c&b&a))&(~(~d&c&a))&(~(c&(~b)&a))); 
endmodule
*/

## Output:

Truthtable
![tt2](https://user-images.githubusercontent.com/59290560/167337576-64d5820b-01a1-4fb8-a779-0596859b8c4d.png)



##  RTL realization:

![rtl2](https://user-images.githubusercontent.com/59290560/167337693-a5e7216d-5832-41f3-8411-99cc1d3a327e.png)

## Timing diagram 
![td2](https://user-images.githubusercontent.com/59290560/167337931-cadd9470-41b9-456b-95a0-f65d70ffc432.png)

## Result:
 The given logic function is implemented using NAND and NOR gates and it is verified successfully in Quartus using Verilog programming.
