A fibonachi number sequence validator written in Y86-64 for a university class.

Specifications of the assignment are as followed:
Numbers must be input in an array  
Starts from non-zero number  
If a valid fibonachi number is found, the program will continue on  
If a non-fibonachi number is found, then the input number is set to %rax and program halts  
Otherwise, the end of the number sequence input into the program must end with a zero. If the program doesn't find any problematic numbers, then it sets the last number of the sequence (the zero) to %rax, which means that the program is finished and the numbers of the sequence were all valid fibonachi numbers.
