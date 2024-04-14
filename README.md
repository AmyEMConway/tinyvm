One paragraph stating what my program is doing:
I am using c programming language to write a program that simulates a variant of the Tiny Harvard Architecture. The code is implementing the basic instruction set of the Tiny Machine Architecture which are LOAD, ADD, STORE, SUB, IN, OUT, END, JMP and SKIPZ. The registers are all being represented in the code. The IM size is 250 and the DM size is 10. All the CPU registers and DM are of type int. My input file “elf.txt” contains the data that will help assist my program in being able to multiply two numbers.  

What opcodes does your tiny virtual machine adhere to?
OPCODE	MNEMONIC	MEANING
01	  LOAD X    A <— DM[x]
02	  ADD X	    A <— A + DM[x]
03	  STORE X	  DM[x] <— A
04	  SUB X	    A <— A – DM[x]
05	  IN X	    A <— read from device
06	  OUT X	    A —> output to device
07	  END	      STOP
08	  JMP	      PC <— x
09	  SKIPZ	    If z = 1 skip to next instruction


Assignment: Homework 4 

Author: Amy Conway

School: University of Central Florida

Professor: Euripides Montagne
Class: CGS 3269
Due Date: April 14, 2024

Language: C
To compile: gcc tinyvm.c -o tinyvm
To Execute: ./tinyvm elf.txt
Note: I used vscode on a MAC laptop to make/compile my code. Make sure that the files are all in the same place. Then click run. When you click run nothing will come up in the output so go to the terminal. When in the terminal do these steps for a MAC laptop:
1.	Do the command line that makes sure you are in the right place for example ( cd desktop/MyTinyVm) this is the folder where everything is. 
2.	Do the command line to compile ( gcc tinyvm.c -o tinyvm)
3.	Do the command line to execute ( ./tinyvm elf.txt)
4.	Follow the steps that pop up.

