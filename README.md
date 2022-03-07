# N_Bit_Arithmetic_Logical_Unit

N Bit Arithmetic Logic Unit implemented using Verilog for the Computer Organization and Architecture Course

Implement an ALU that supports the following 8 operations:
* Adding two N-bit numbers.
* Subtracting two N-bit numbers.
* Adding 1 to a N-bit number.
* Subtracting 1 from a N-bit number.
* Bitwise ANDing two N-bit numbers.
* Bitwise ORing two N-bit numbers.
* Bitwise XORing two N-bit numbers.
* Arithmetic shifting right of a N-bit number that will discard the least significant bit.
The output of the ALU must be a (N+1)-bit number, where the additional bit is the most significant one.

selection inputs              operation

s0     s1     s2              output

0      0      0                a+1

0      0      1             shift right (a)

0      1      0                 a+b

0      1      1                 a-b

1      0      0                 a-1

1      0      1               a and b 

1      1      0               a or b

1      1      1               a xor b


