# ATM-Simulation
Simulates an ATM system in Python for depositing, withdrawing funds (with error handling), and processing transactions from a file, timestamping and saving each for record-keeping.

# Features
Deposit and Withdrawal: Users can deposit and withdraw funds, with the balance updated accordingly.
Error Handling: The system raises a custom InsufficientFundsError when a withdrawal exceeds the available balance.
Transaction Processing: Transactions can be processed from a text file (transactions.txt), with actions like deposit and withdraw executed based on the file content.
Transaction Logging: Each transaction, along with a timestamp, is logged to a file (saved_transactions.txt) for audit purposes.

# Technologies Used
Python: Programming language used for scripting and development.
Datetime: Module for handling date and time operations.
Exception Handling: Custom InsufficientFundsError class for managing insufficient balance scenarios.
File Handling: Operations to read transactions from and save transactions to text files.

# How to Use
Running the Code: Execute the script to test the ATM functionalities.
Copy code
python atm_simulation.py
Testing: The script includes a test_ATM() function that demonstrates deposit, withdrawal (including error handling), transaction processing from file, and transaction logging.

# Notes
Adjust file paths (transactions.txt, saved_transactions.txt) as per your environment.
This project demonstrates fundamental concepts in Python programming, including object-oriented design, exception handling, and file operations.
