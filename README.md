# CPU with SUS architecture
## General
I and @markiyceresk are making a 4-bit CPU in Minecraft. It uses **SUS**[^1] instruction set architecture.
## CPU
*CPU documentation will be added soon*
## SUS assembly
As CPU is 4-bit (*byte = 4 bits*) 2<sup>4</sup> = 16 instructions (*commands*) are available. They are listed here:
```
0000 - separator between commands
0001 - "move value" - mov
0010 - "move variable" - mvv
0011 - "bitwise AND" - and
0100 - "bitwise OR" - or
0101 - "additon" - add
0110 - "create mark" - mark
0111 - "jump unconditionally" - jmp
1000 - "compare" - cmp
1001 - "jump if greater" - jmg
1010 - "jump if equal" - jme
1011 - "jump if less" - jml
1100 - "input/output variable value" - io
1101 - "invert pixel at cursor" - wpx
1110 - "clear screen" - clear
1111 - "move cursor" - cur
```
More about **SUS** assembly [here](docs/SUS-ASM.pdf).

[^1]: **SUS** stands for *Set of Unrelated Statements*
