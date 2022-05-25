# Binary_to_Gray_conversion
A Program for Binary to Gray conversion in Assembly language . Algorithm for Binary-Gray conversion is given below and it can be easily implemented by this algorithm .


# Algorithm for Binary to Gray conversion
 

Step I : Get the number whose gray code equivalent is to be found.

Step II : Add number with itself.

Step III : XOR this added result with the original number.

Step IV : Shift the XOR ed number by 1 bit position to the right to get the Gray equivalent.

Step V : Display the result.

Step VI : Stop.



## How to Run this Program
 

For Running this program you should have installed Tasm on you computer .

C:\programs>tasm bin-gray.asm

Turbo Assembler Version 3.0 Copyright (c) 1988, 1991 Borland International

Assembling file: bin-gray.asm

Error messages: None

Warning messages: None

Passes: 1

Remaining memory: 438k

C:\programs>tlink bin-gray.obj

Turbo Link Version 3.0 Copyright (c) 1987, 1990 Borland International

Warning: No stack

C:\programs>bin-gray

0F
