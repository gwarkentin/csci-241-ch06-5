# csci-241-ch06-5
Boolean_Calculator 

This is a good exercise to use a table-driven selection. You can download the stub file ch06_06stub.asm that provides the main menu code and a table-driven structure. Your programming is to fill out all the blank procedures. Before working, please download and play this ch06_06.exe to make sure that you understand what you are going to create! The following is just an example when you first hit 2 to do OR and then hit 3 to do NOT.

Hint: ReadHex and WriteHex are handy.
---- Boolean Calculator ----------
1. x AND y
2. x OR y
3. NOT x
4. x XOR y
5. Exit program

Boolean OR
Input the first 32-bit hexadecimal operand:  00008Af2
Input the second 32-bit hexadecimal operand: 0000FF00
The 32-bit hexadecimal result is:            0000FFF2

---- Boolean Calculator ----------
1. x AND y
2. x OR y
3. NOT x
4. x XOR y
5. Exit program

Boolean NOT
Input the first 32-bit hexadecimal operand:  002f45bb
The 32-bit hexadecimal result is:            FFD0BA44
Advanced consideration: A possible issue is that so much repeated code would be in multiple operation procedures for AND, OR, etc., such as input and output. How to avoid and how to solve this with DRY?
