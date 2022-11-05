# square-submatrix
Write a program to, given a square matrix with elements of 0 or 1, find the first square submatrix with all 1 elements. This square submatrix should be as big as it can be, but it must include only ones and be at least 3
in size. Your program should prompt the user to enter the number of rows in the matrix. The number of rows
should be at least 5. The program then displays the location of the first element in the square submatrix and
the number of the rows in the submatrix. Here is a sample run:
Example 1:
Enter the number of rows in the matrix: 6
Enter the matrix row by row:
101011
111011
101111
101111
101111
111111
The first square submatrix is at (2, 2) with size 4
Example 2:
Enter the number of rows in the matrix: 6
Enter the matrix row by row:
101011
111011
101111
101111
101111
111101
The first square submatrix is at (2, 2) with size 3
Example 3:
Enter the number of rows in the matrix: 7
Enter the matrix row by row:
1111111
1111111
1111111
1011111
1011111
1111111
1111111
The first square submatrix is at (0, 0) with size 3
Your program should implement and use the following method to find the first square submatrix with the
minimum size 3.
def find_first_squareblock(matrix : list[int]) -> list[int]
The return value is a list that consists of three values. The first two values are the row and column indices for
the first element in the submatrix, and the third value is the number of the rows in the submatrix.
