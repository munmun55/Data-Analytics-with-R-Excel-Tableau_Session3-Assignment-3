# Data-Analytics-with-R-Excel-Tableau_Session3-Assignment-3
Data-Analytics-with-R-Excel-Tableau_Session3 Assignment 3 Description


The R-script for the given problem is as follows:


rep(1:5, 4)     # replicating the sequence 1 to 5

mymat <- matrix(rep(1:5 ,4), nrow = 4 , ncol = 5, byrow = TRUE )  
 
mymat

apply(mymat, 1, sum)     # sum of rows 

apply(mymat, 2, sum)     # sum of columns



Explanation:

•	Here , matrix mymat is created by replicating the sequence of 1 to 5 (1,2,3,4,5) for 4 times by using rep(1:5 ,4).

•	The matrix mymat is of order 4X5 (4 rows and 5 columns)

•	The sum over  rows and columns is found by apply() function using the r-commands as follows:
o	apply(mymat, 1, sum)     # sum of rows 
o	apply(mymat, 2, sum)     # sum of columns
Here,1 is used for rows and 2 is used for columns.
