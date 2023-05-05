Download Link: https://assignmentchef.com/product/solved-cse100-lab-8-matrix-chain-multiplication
<br>
<h1>Dynamic Programming: Matrix Chain Multiplication</h1>

<strong>Description </strong>In this assignment you are asked to implement a dynamic programming algorithm for the matrix chain multiplication problem (chapter 15.2), where the goal is to find the most computationally efficient matrix order when multiplying an arbitrary number of matrices in a row. You can assume that the entire input will be given as integers that can be stored using the standard C++ int type and that matrix sizes will be at least 1.

<strong>Input </strong>The input has the following format. The first number, <em>n</em>≥ 1, in the test case will tell you how many matrices are in the sequence. The first number will be then followed by <em>n </em>+ 1 numbers indicating the size of the dimensions of the matrices. Recall that the given information is enough to fully specify the dimensions of the matrices to be multiplied.

<strong>Output </strong>First, you need to output the minimum number of scalar multiplications needed to multiply the given matrices. Then, print the matrix multiplication sequence, via parentheses, that minimizes the total number of number multiplications. Each matrix should be named A#, where # is the matrix number starting at 0 (zero) and ending at <em>n</em>−1. See the examples below.

<strong>Examples of input and output</strong>

2

2 3 5

30

(A0A1)

3

10 100 5 50

7500

((A0A1)A2)

3

10 30 5 60

4500

((A0A1)A2)

6

30 35 15 5 10 20 25

15125

((A0(A1A2))((A3A4)A5))

See the lab guidelines for submission/grading, etc., which can be found in Files/Labs.