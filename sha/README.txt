This File contains the Details for, Execution of the Program, What we did in the program to get the Optimized one ?, 
How we approached the Optimization for the program ?, 
How much difference is there in Running Time of the Program?

Program File Details:

shaO.c - Original File which was given by Professor.
shaM.c - Modified File which contains the Optimized C program Code.
-----------------------------------------------------------------------------------------------------------------------------------------------------
How to Run the shaM.c program ?

There are two Steps for the Running the shaM.c file program:

Step 1: Compilation Part for shaM.c file

Give the command as gcc shaM.c -o programM
where,
shaM is the C program file.
programM is the Compiled File.

Step 2: Execution Part for shaM.c file

Give the command as ./programM
where,
programM is the file which is going to show output.
----------------------------------------------------------------------------------------------------------------------------------------------------
How to Run the shaO.c program ?

There are two Steps for the Running the shaO.c file program:

Step 1: Compilation Part for shaO.c file

Give the command as gcc shaO.c -o programO
where,
shaO is the C program file.
programO is the Compiled File.

Step 2: Execution Part for shaO.c file

Give the command as ./programO
where,
programO is the file which is going to show output.
----------------------------------------------------------------------------------------------------------------------------------------------------

How we approached the Optimization for the program ?

When we Saw the program, We decided to change only the FOR Loops. 
Because Loops has O(n) Time Complexity and Function blocks without the Looping Statments is going to have O(1). 
Where '(1)' Constant time taken for running the Function block
Where '(n)' represents the Number of times the loop is going to run.
----------------------------------------------------------------------------------------------------------------------------------------------------
What we did in the program to get the Optimized one ?

We removed For Loops from the functions in the program. 
We then manually run the looping statements as the number of times required for the function Block of the program.
Finally, We reduced the Running time of the program.
-----------------------------------------------------------------------------------------------------------------------------------------------------








