A. Defining the Superclass
Design a class named Account that contains:
• A private int data field named id for the account (default 0).
• A private double data field named balance for the account (default 0.0).
• A private double data field named annualInterestRate that stores the current interest rate
(default 0.0).
• A no-arg constructor that creates a default account.
• A constructor that creates an account with the specified id, initial balance and annual interest
rate.
• The accessor and mutator methods for id, balance, and annualInterestRate.
• A method named getMonthlyInterestRate() that returns the monthly interest rate.
monthlyInterestRate is annualInterestRate / 12. Note that annualInterestRate is a percentage
e.g., like 4.5%. You need to divide it by 100
• The method getMonthlyInterestAmount() is to return monthly interest amount, not the interest[CSE110_Lab06__.pdf](https://github.com/NishatVasker/Bank-Account/files/7613797/CSE110_Lab06__.pdf)

rate. Monthly interest amount is balance * monthlyInterestRate.
• A method named withdraws that withdraws a specified amount from the account.
• A method named deposit that deposits a specified amount to the account
Write a test program that creates an Account object with an account ID of 1122, a balance of $20,000,
and an annual interest rate of 4.5%. Use the withdraw method to withdraw $2,500, use the deposit method to
deposit $3,000, and print the ID, balance and the monthly interest of the Account.
B. Creating the Subclasses
Create two subclasses for checking and saving accounts named as Checking Account and Savings
Account.
• A checking account has an overdraft limit which is double type variable.
• A savings account has issued with a credit card automatically. It holds the 16-digit card number. Savings
Account class must have a method getCreditBalance that returns a credit balance which is three times of
the current balance in the account.
