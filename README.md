 Fall 2019
Programming Project #1

This assignment must be completed and turned in before 6:00am on Monday, Sept. 16, 2019

Assignment Overview

This assignment will give you experience in the use of C++ console input/output, conditionals, loops and the Unix environment. The program will be an interactive menu-driven program that displays a menu and performs the following functionality:

•	A menu option that the user can choose to calculate the monthly payment on a mortgage loan for a house.
o	If this option is chosen, your program will prompt the user for the yearly interest rate, the loan amount, and the total number of payments.10 POINTS
o	To calculate and display the monthly payment you will use the following formula: 10 POINTS
monthlyPayment = (loan_amount * monthlyInterestRate)/(1-(1+monthlyInterestRate)-t))
                          Note: monthlyInterestRate is computed by (yearly interest rate /100)/12

•	A menu option that the user can choose to calculate the future value of an investment.
o	If this option is chosen, your program will prompt the user for the annual interest rate, the number of years for the investment and the amount of the original investment. 10 POINTS
o	To calculate and display the future value, your program will use the following formula:
The present value (PV) is the amount that is to be invested today. The interest rate (i) is the annual interest rate. Time (t)  is the length of time (number of years) in the future. 10 POINTS
 FV = PV*(1+i)t
Note: To convert annual interest rate entered as a percent  you must divide it by 100.

•	A menu option that the user can choose to calculate the present value for a future need.
o	If this option is chosen, your program will prompt the user for the interest rate, the number of years until a future value is realized, and the amount of the future value.  10 POINTS
o	To calculate and display the present value to realize a future need, your program will use the following formula: 10 POINTS
The future value (FV) is the amount that you want to have in the future. The interest rate (i) is the annual interest rate. Time (t)  is the length of time (number of years) in the future you want to realize the future value.
PV = FV/(1+i)t
Note: To convert annual interest rate entered as a percent you must divide it by 100.

  Project Specifications:

1.	Your program does not have to contain programmer defined functions but may.
2.	Your menu must continue to display, allowing the user to enter another option until   the user decides to quit. 5 POINTS
3.	Once the calculations are performed, your program should display the labelled amounts that the user entered and the calculated values nicely formatted including dollar sign, decimal point and rounding to two decimal places. 5 POINTS
4.	If the user enters an incorrect option, your program should display an error message and ask for the menu choice again until a correct one is entered. 5 POINTS
5.	In order to get the exponential value needed, use the pow function in the cmath library. 5 POINTS

Grading rubrics:

https://s2.smu.edu/~etchison/cse1342/pguide.doc
BE SURE TO TEST THE ABOVE SPECIFIED FUNCTIONALITY THOROUGHLY.

Deliverables:

A .zip file (lastname,firstinitial,p1) containing p1.cpp (your source code solution) and a p1.out ( your executable file)  MUST be uploaded to GitHub.  
•	Source code files compiled in an environment other than UNIX are NOT accepted and will receive a zero. 
•	Source code files that do not compile will receive a zero. 
•	 Source code files that execute and accomplish some but not all tasks correctly will receive partial credit. 
•	You should develop and test the program tasks incrementally such that if you are not able to complete the entire program you can receive partial credit for the completed part.

Due Date Sept.16 6:00AM; late Sept. 18 6:00AM , -30 points






