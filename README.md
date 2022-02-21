# Matrix-operation-in-R

#Answer the following questions and post your answer on your blog:
#1. Consider A=matrix(c(2,0,1,3), ncol=2) and B=matrix(c(5,2,4,-1), ncol=2).
#create a matrix in R
#a) Find A + B
Using ’-‘ operator for matrix subtraction:
#b) Find A - B
using the cbind function to produce matrix
#ncol – this argument is the number of columns in the created matrix
A = matrix(c(2,0,1,3), ncol=2) B = matrix(c(5,2,4,-1), ncol=2)
Using ‘+’ operator for matrix addition
A+B
Using ’-‘ operator for matrix subtraction:
A-B
#2. Using the diag() function to build a matrix of size 4 with the following values in the diagonal 4,1,2,3.
diag() function in R Language is used to construct a diagonal matrix. Syntax: diag(x, nrow, ncol)
diag(x = c(4,1,2,3), nrow = 4, ncol = 4)
#3. Generate the following matrix:
# constructing a diagonal matrix
## [,1] [,2] [,3] [,4] [,5] ## [1,] 3 1 1 1 1 ## [2,] 2 3 0 0 0 ## [3,] 2 0 3 0 0 ## [4,] 2 0 0 3 0 ## [5,] 2 0 0 0 3
X <- diag(x = 3, nrow = 5) X[1, 2:5] <- 1 X[2:5 ,1] <- 2 print(X)
