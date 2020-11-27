# Imaginary numbers

You have just written your first program to determine the approximate value of an irrational number.  An important thing to recognise from the previous exercise is that, just as the set of natural numbers is not closed under the operation of subtraction, the set of rational numbers is not closed under the square root operation.  We thus need to introduce irrational numbers like ![](https://render.githubusercontent.com/render/math?math=\sqrt{2}) to resolve this problem.  

As discussed in the previous exercise, irrational numbers cannot be represented using binary.  We can, however, manipulate expressions involving irrational numbers in a computer if we use symbolic computation.  To see how this works run the code shown in the cell on the left now.  This code uses NumPy and sympy to evaluate the square root of 2.  As you will notice, NumPy outputs the decimal that approximates the value of this irrational. Sympy, however, which is able to do symbolic computation, outputs the irrational number `sqrt(2)` directly.

Notice that once the irrational numbers are included the set of all real numbers is still not closed under the square root operation as there no real number is equal to the square root of minus one.  __To complete this task (and the whole exercise) adjust the code on the left to "calculate" the square root of -1 using sympy and numpy.__  Consider the two results you obtain.  The result you obtain using sympy will be investigated further in later parts of the course.
