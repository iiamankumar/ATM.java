ATM.java

A simple Java program that simulates an ATM (Automated Teller Machine). This program allows users to perform basic banking operations, such as checking their account balance, depositing money, and withdrawing money.

Features

Check Balance: View the current account balance.
Deposit Money: Add money to the account.
Withdraw Money: Withdraw a specified amount from the account.
Getting Started

Prerequisites
To run this project, ensure you have the following installed:

Java Development Kit (JDK) (version 8 or higher)
A code editor or IDE (e.g., IntelliJ IDEA, Eclipse, or a text editor like VS Code)

How to Use

Once the program starts, you will be presented with a menu to choose from the following options:
Check Balance: Displays your current account balance.
Deposit Money: Prompts you to enter an amount to deposit into your account.
Withdraw Money: Prompts you to enter an amount to withdraw. (Ensure you have sufficient funds to complete the withdrawal.)
Exit: Exit the program.

Code Overview

The ATM.java program is structured as follows:

Variables:
balance: Holds the account's current balance.
Methods:
checkBalance(): Displays the current balance.
deposit(double amount): Adds the specified amount to the balance.
withdraw(double amount): Deducts the specified amount if sufficient funds are available.
main(String[] args): Provides the main menu and handles user input.

Future Enhancements

Some potential features for future updates include:

Support for multiple accounts.
Persistent storage to save balances between sessions.
User authentication with PINs or passwords.
Enhanced error handling for invalid inputs.
