Banking System
About the Program

This is a simple Python program that demonstrates Object-Oriented Programming (OOP) using classes and objects.

The program represents a basic banking system where a customer has a bank account and can make deposits and withdrawals.

Classes Used

The program contains three classes:

1. Account:custmers bank account information, 

The Account class stores the customer's bank account information: account number, balance
The class has three main functions:
deposit() – adds money to the account.
withdraw() – removes money from the account if there is enough balance.
display_balance() – displays the current account balance.



2.The Customer class
it stores information about the customer.

The display_customer_info() function displays the customer's name and account balance.

3. Transaction class:
It handles deposits and withdrawals.
It includes:
account – identifies which account is being used.
amount – stores the amount of money involved.
transaction_type – identifies whether the transaction is a deposit or withdrawal.

The process_transaction() function checks the transaction type and performs the correct operation.

OOP Concepts Demonstrated

This program demonstrates:

Classes – Account, Customer, and Transaction
Objects – account1, customer1, transaction1, and transaction2
Attributes – account number, balance, name, amount, and transaction type
Methods – functions inside the classes
Constructors – __init__() is used to initialise objects
Objects working together – the Customer uses an Account, and Transaction operates on the Account
How to Run
Open the Python file in VS Code or Jupyter Notebook.
Run the program.
The program will create the account and customer.
It will perform a deposit and withdrawal.
The final account balance will be displayed.
What I Learned

I learned how classes and objects can be used to represent real-world situations. I also learned how different classes can work together, such as a customer having an account and transactions changing the account balance.



                                          
