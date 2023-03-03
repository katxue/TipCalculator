# TipCalculator
Problem Statement:
You're out to eat with friends and want to split the bill, but you're not sure how much to tip. Write a C++
program that calculates the tip amount based on the total bill and the number of people splitting the bill.
The program should prompt the user to input the following information:
1. The total bill amount
2. The number of people splitting the bill
3. Tip percentage
The program should then calculate the recommended tip and the total amount owed by each person.
The program should output the following information:
1. The total bill amount
2. Tip amount
3. Total amount owed by each person
At the end of each calculation, the user should be asked if they want to do another calculation or exit the
program. The program must handle all types of bad inputs from user and recover from the errors.
Example run: (User inputs are highlighted!)
Enter the total bill amount: 4fdd555
Invalid input! Bill amount must be a float/double!
Enter the total bill amount: 150.88
Enter the number of people splitting the bill: 5.6
Invalid input! Number of people must be a positive integer!
Enter the number of people splitting the bill: 0
Invalid input! Number of people must be a positive integer!
Enter the number of people splitting the bill: 8
Enter the tip percentage, between 1 to 100 (i.e., for 15%, enter 15): 15
Total bill amount: $150.88
Tip amount: $22.63 (15%)
Total amount owed by each person: $21.69
Do you want to do another calculation? (0-no, 1-yes): 0
Required function(s):
Your program must involve the following functions. You may not change the parameters or the return
type!!!
//a function to get bill amount from the user
double get_bill();
OR
void get_bill(double& bill_amount);
//a function to calculate the tip amount
double calculate_tip (double bill_amount, double tip_percentage);
OR
void calculate_tip (double bill_amount, double tip_percentage, double& tip);
