# ATMinterface
# ATM Interface Project in Java

The ATM Interface project in Java is a software application that simulates the functionality of an Automated Teller Machine (ATM). It allows users to perform various banking operations, such as withdrawing cash, depositing funds, checking account balance, and transferring money between accounts.

The project utilizes Java programming language and follows object-oriented principles to design and implement the ATM interface. It provides a user-friendly command-line interface that prompts users for input and displays appropriate messages and results.

## Features

The ATM Interface project includes the following features:

1. Account Creation: Users can create new bank accounts by providing necessary details like account number, name, PIN, and initial deposit amount.

2. Account Login: Existing account holders can log in to their accounts by entering their account number and PIN.

3. Cash Withdrawal: Users can withdraw a specific amount of cash from their account balance, provided they have sufficient funds.

4. Cash Deposit: Users can deposit a certain amount of cash into their account.

5. Balance Inquiry: Users can check their account balance, which displays the current available balance.

6. Funds Transfer: Users can transfer funds from one account to another, either within the same bank or to another bank account, by providing the recipient's account number and the transfer amount.

7. PIN Change: Account holders can change their PIN to enhance account security.

8. Transaction History: Users can view their transaction history, which displays the details of their past transactions, such as date, time, type, and amount.

## Project Structure

The project can be organized into the following components:

1. `Main`: The main class of the project that contains the entry point for the application. It handles user input and invokes appropriate methods based on the selected operation.

2. `Account`: This class represents a bank account and contains attributes like account number, name, PIN, and balance. It also includes methods for depositing, withdrawing, transferring funds, and updating the PIN.

3. `Bank`: The `Bank` class is responsible for managing multiple accounts. It provides methods for creating new accounts, authenticating users during login, and maintaining the overall account database.

4. `Transaction`: This class represents a single transaction and includes attributes such as transaction type (withdrawal, deposit, transfer), amount, and timestamp.

5. `TransactionHistory`: The `TransactionHistory` class manages the transaction history for each account. It includes methods for adding new transactions, retrieving transaction details, and displaying the history.

6. `InputHandler`: This class handles user input validation and parsing. It ensures that the user provides valid inputs for account numbers, PINs, amounts, etc.

7. `Utils`: The `Utils` class contains utility methods used throughout the project, such as formatting dates, displaying messages, and generating unique transaction IDs.

## Getting Started

To run the ATM Interface project, follow these steps:

1. Install Java Development Kit (JDK) on your system if not already installed.

2. Set up your preferred Java development environment (IDE) or use a text editor.

3. Create a new Java project and import the project files.

4. Build the project to ensure there are no compilation errors.

5. Run the `Main` class to start the ATM interface.

## Conclusion

The ATM Interface project in Java provides a basic implementation of an ATM system. It allows users to perform various banking operations through a command-line interface. You can further enhance the project by adding features like account locking after multiple failed login attempts, implementing security measures, and integrating with a backend database for persistent data storage.
