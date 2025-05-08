Programming in MIPS32 assembly (task lists)
More advanced solutions will result with higher grades.

List 0 (06.05.2021):
Familiarization with registry concepts and types of registers, memory pyramid, processor work cycle and MARS simulator. Run any program in MARS; continuous and step-by-step simulation. (done during initial exercise)
You do not need to send any solution file to the teacher.

List 1 (13.05.2021):
Please write a program calculating the value of the third degree polynomial for the given parameters a, b, c, d and x. The form of a polynomial: y = ax^3 + bx^2 + cx + d.

List 2 (20.05.2021):
Please write a program that asks the user for the value N>0, then calculates and displays the value N! (factorial of N). Secure the program against the overflow problem (best: chcek for overflow after each multiplication). Write the program in two versions "do-while" and "while-do". Answer the question: for what maximum value of N the program gives the correct value of N!. 
Optional: prepare version of the above program that calculates N! for N up to 50.

List 3 (27.05.2021):
Please write a program that asks you to enter N<100, then reads N integers from the keyboard, sorts them in ascending order and displays a sorted sequence of numbers on the screen (preferably separated by commas). Sorting algorithm: bubble-sort (or more advanced if you like).

Please write two versions of the above program:
A.) without calling subroutines. Only the Sort procedure is called between the reading input data and printing of results.

B.) with calling two subroutines. Sort and Swap procedures whould be prepared. The swap procedure swaps two numbers and is called by the Sort procedure when the order of the two numbers should be changed. The Sort procedure is called as in the version with only one subprocedure. Note the need of preservation of the contents of the return register ($ra).

Optional: For those willing to solve additional task: write the swap procedure without using an additional buffer.

Test (02.06.2021)

List 4 (10.06.2021):
Please write a program that asks to enter a number N<1000 and then checks if the number is a prime number or not. If the number is a prime the program should output "This is a prime number" and in other case it should output "This is not a prime number".

List 5 (17.06.2021):
Please write a program that asks to enter two sparse vectors, and then calculate their scalar product. The sparse vector in its simplest version can be stored in memory as a pair of vectors - a value vector and an order vector with the same number of dimensions. More memory-saving solutions will be scored higher.

=== EOL ===
