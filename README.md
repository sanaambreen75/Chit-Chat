Banking System
About the Program

This is a simple Python program that demonstrates Object-Oriented Programming (OOP) using classes and objects.

The program represents a basic banking system where a customer has a bank account and can make deposits and withdrawals.

Classes Used

The program contains three classes:

1. Account

The Account class stores the customer's bank account information.

It includes:

account_number – stores the account number.
balance – stores the current account balance.

The class has three main functions:

deposit() – adds money to the account.
withdraw() – removes money from the account if there is enough balance.
display_balance() – displays the current account balance.
2. Customer

The Customer class stores information about the customer.

It includes:

name – stores the customer's name.
account – connects the customer to their bank account.

The display_customer_info() function displays the customer's name and account balance.

3. Transaction

The Transaction class handles deposits and withdrawals.

It includes:

account – identifies which account is being used.
amount – stores the amount of money involved.
transaction_type – identifies whether the transaction is a deposit or withdrawal.

The process_transaction() function checks the transaction type and performs the correct operation.

How the Program Works

The program first creates an account for the customer:

account1 = Account(account_number=101)

Then it creates a customer and connects the customer to the account:

customer1 = Customer(name="Alice", account=account1)

The program displays the customer's starting balance:

Customer Name: Alice
Account 101 balance: $0

A deposit transaction of $50 is then made:

transaction1 = Transaction(account1, 50, "deposit")

The balance becomes:

$50 deposited. New balance: $50

A withdrawal of $30 is then made:

transaction2 = Transaction(account1, 30, "withdraw")

The final balance becomes:

$30 withdraw. New balance: $20
Example Output
Customer Name: Alice
Account 101 balance: $0

$50 deposited. New balance: $50

$30 withdraw. New balance: $20

Customer Name: Alice
Account 101 balance: $20
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
