ASSUMPTIONS:

1. There should be nothing other than .text and .data on a line.
2. There must be commas in instruction.
3. Instructon label is written in the same line as the instruction itself. Similarly for variable name.
4. .asciiz variables are enclosed in ""
5. Elements of array are seperated by ' ', not by comma.
6. Put no ':' in comments.

FOR-REFERENCE:

1. Assembler directives:
	.word	.half	.dword	.byte	.asciiz	  .data	  .text
2. Has support for binary and hex values. They begin with 0x, 0b.
3. After string variable, one byte in memory is left vacant, just like in Venus.
4. Code segment is stored as unsigned bytes in memory.
5. In auipc and lui, only positive imm field accepted(range:[0,2^20-1]), just like in Venus.
6. Label name cannot begin with a digit, and cannot contain any ()
7. In case of an INFINITE LOOP, program can be EXITED by pressing STOP button.