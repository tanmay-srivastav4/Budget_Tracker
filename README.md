# Budget Tracker

A simple Python-based application to manage user's budget by tracking expenses, calculating totals, and showing your remaining balance. The data is saved to a JSON file, ensuring persistence across sessions.


## Features
- **Set Initial Budget**: Input your total budget for tracking.
- **Add Expenses**: Log expenses with a description and amount.
- **View Budget Details**: See your total budget, expenses, total spent, and remaining balance.
- **Data Persistence**: All data is saved in a JSON file (`budget_data.json`) for easy reusability.
- **User-Friendly Interface**: Simple menu-driven application to guide the user.



## Prerequisites
- Python 3.x installed on your system.



## How to Run
1. Clone or download the repository containing this script.
   ```
   git clone https://github.com/tanmay-srivastav4/Budget_Tracker
   ```
2. Open a terminal or command prompt and navigate to the folder where the script is saved.
   ```
   cd Budget_Tracker
   ```
3. Run the script using the following command:
   ```
   python budget_tracker.py
   ```

  
## How to Use
- **Initial Setup**: If it's the user's first time running the app, they'll be prompted to enter their initial budget. This value is saved for future sessions.
- **Menu Options**:
    - Option 1: Add an Expense
        - Enter a description (e.g., "Groceries") and the expense amount.
        - The expense will be saved to the user's budget data.
    - Option 2: Show Budget Details
        - View the total budget, all logged expenses, total spent, and remaining balance.
    - Option 3: Exit
        - Save the budget data to a JSON file (budget_data.json) and exit the application.

## Example Usage
   ```
   Welcome to the Budget App

   What would you like to do?
   1. Add an expense
   2. Show budget details
   3. Exit
   Enter your choice (1/2/3): 1
   Enter expense description: Groceries
   Enter expense amount: 150
   Added expense: Groceries, Amount: 150
   ```
