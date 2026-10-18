Full Adder Using Tanner EDA Tools

Aim:
To design a Full Adder circuit and study its output using Tanner EDA tools.

Description:
A Full Adder is a combinational circuit that adds three 1-bit inputs: A, B, and Carry-in (Cin). It produces two outputs: Sum and Carry-out (Cout).

Boolean Expressions:
                     Sum: S = ~(A)BC + A~(B)C + AB~(C) + ABC
                     Carry-out: Cout = AB + AC + BC
                 

Truth Table:
             |  A  |  B  |  Cin  |  Sum  |  Cout  |
             |  0  |  0  |   0   |   0   |   0    |
             |  0  |  0  |   1   |   1   |   0    |
             |  0  |  1  |   0   |   1   |   0    |
             |  0  |  1  |   1   |   0   |   1    |
             |  1  |  0  |   0   |   1   |   0    |
             |  1  |  0  |   1   |   0   |   1    |
             |  1  |  1  |   0   |   0   |   1    |
             |  1  |  1  |   1   |   1   |   1    |

Tools Used:
           * S-Edit: Circuit design
           * T-Edit:  Netlist
           * W-Edit: Waveform observation

Implementation:
1. Designed the Full Adder circuit in S-Edit.
2. Prepared the circuit netlist in T-Edit.
3. Observed the input and output waveforms in W-Edit.
4. Compared the outputs with the Full Adder truth table.

Examples of Input and Output:
 * Example 1: A = 0, B = 0, Cin = 1 → Sum = 1, Cout = 0
 * Example 2: A = 0, B = 1, Cin = 1 → Sum = 0, Cout = 1
 * Example 3: A = 1, B = 1, Cin = 1 → Sum = 1, Cout = 1

Result:
The Full Adder circuit is designed to perform binary addition of three 1-bit inputs and generate Sum and Carry-out outputs.

Applications:
* Digital arithmetic circuits
* Adders in processors
* Arithmetic Logic Units (ALUs)
