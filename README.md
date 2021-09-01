# C-Library-for-INTAL---INTegers-of-Arbitrary-Length
A C library for INTAL-INTegers of arbitrary length (“INTAL” in short for integers of arbitrary length). The functionality of the library is to perform arithmetic operations like Addition , Subtraction , Multiplication , Division and Exponentiation .

# Assumption
The length of input taken by code is limited by range of malloc function (used in the code)

The range of exponent in the power fuction is limited by the range of size of the integer.

The user enters valid inputs/integers , such as 1233 , rather than 1+23 or 1sd32 , which 
aren’t integers.

The user enters new values into the intal_demo.c file , and compiles and runs the file 
for those inputs.

# Changes made in the original template –
there was one change which I made in the read_intal functin.
In that , he hadn’t assigned the value of strlen(a->s)-1 back to a->n . also , I had to make 
changes to the read_intal function , as in the struct definition , it had specified that the 
sign should not be included in a->n , but it was included in the read_intal function.

# Approach 
1. Write a function to declare and initialize INTALs.
2. Write a function to compare INTALs; returns equal, lesser than or greater than comparisons of inputted numbers.
3. Implement basic arithmetic operations on INTAL : Addition, Subtraction, Multiplication.
4. Implement applications of INTAL: Division, Exponentiation.

# Addition function

# Subtraction function

# Multiplication function

# Division function

# Exponentiation function









