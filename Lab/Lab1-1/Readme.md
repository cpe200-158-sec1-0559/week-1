﻿# Instruction

## Read and understand the code, the logic behind it, the limitation of it
* Answer the question 1 - 4 below (you can edit this file directly)
* Change the code such that it will sort from larger to smaller, put the revision of your code below
* Change the code such that there is no flag variable, put the commit number below and answer question 5 


## Revision, put your commit number here
* Sort from larger to smaller: c9c8566ace854a310d738da3ec0e91ae30a97e72
* Without flag: 391f21c1497f391c7b614b6d32cbbade72b99969

## Questions
1. How this code can sort number from smaller to larger
 
Answer: This program will transposition number in array when previous number is more than next number, if not it will use WHILE LOOP to recheck and sort these number again.

2. What if two numbers equal, what will happen? 

Answer: Number in position i will not transposition to i+1 (stay in current position).

3. How many times at line 24 will be executed (as a function of the size of input) 

Answer: Executed between n-1 to (n-1)^2 time(s) when n is size of input.

4. Why we need flag variable ? 

Answer: We do not want to processing all case EVEN all number are sorted. So if these number are correctly sorted, Flag variables will be FALSE (TRUE if not) and it will break all loop to next process.

5. When we remove the flag variable, the code will run faster or slower? in which scenario? 

Answer: Slower because EVEN it were sorted, it will run all case (processing up to max times).
