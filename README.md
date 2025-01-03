# expense-tracker
This project is a Monthly Expenses Tracker application built using Tkinter, a Python GUI library. The application allows users to manage and monitor their monthly expenses by adding, updating, and deleting records of their expenditures. It also provides a summary of total expenses and remaining balance.

Key Features:
User Interface:

A Tkinter-based GUI with entry fields for item details and buttons for actions such as saving, updating, and deleting records.
A Treeview widget to display all the expense records in a tabular format.
Core Functionalities:

Add Expense: Users can input item names, prices, and purchase dates, then save the record to a local SQLite database.
View Expenses: All saved expense records are displayed in a scrollable table.
Edit Expenses: Users can select a record, modify it, and save the updates.
Delete Expenses: Selected records can be removed from the database.
Summary Features:

Total Balance: Calculates and displays the remaining balance from a preset monthly budget (default is 5000).
Total Expenses: Computes and displays the sum of all expenses.
Utility Functions:

Current Date: Automatically fills the purchase date field with the current date.
Clear Entries: Clears all input fields for fresh data entry.
Data Management:

SQLite Database Integration:
Records are stored in a database (database.db).
CRUD (Create, Read, Update, Delete) operations are performed via a Database class in the mydb module.
Interactivity:

Records in the Treeview table are selectable for editing or deletion.
Buttons trigger specific actions, providing a seamless user experience.
Real-time Refresh:

The table updates dynamically after each operation to reflect the latest data.
Technologies Used:
Python:
Tkinter for the graphical user interface.
SQLite for database management.
Datetime Module for handling dates.
Custom Modules:
mydb: A custom Python module for interacting with the SQLite database.
