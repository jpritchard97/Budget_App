# Budget Management App

## Overview:
This is a simple Python-based budget management app that helps users keep track of their expenses and remaining budget. The user can input a budget, add expenses, view details of their spending, and see how much of their budget remains. Data can be loaded from and saved to a JSON file to maintain persistence between sessions.

### Features:
1. **Add an Expense**: Users can add an expense with a description and amount.
2. **Show Budget Details**: View the total budget, all expenses, total amount spent, and the remaining budget.
3. **Save and Load Data**: The app can save the current budget and expenses to a JSON file and load them when the program is restarted.
   
### How to Use:
1. **Run the Program**: Execute the script and input your initial budget.
2. **Add Expenses**: Select the option to add expenses by providing a description and amount.
3. **View Budget Details**: Select the option to see a summary of the budget and expenses.
4. **Exit**: Exit the program when done. You can modify the script to save the data if needed.

### Sample Flow:
1. Input your initial budget.
2. Add expenses.
3. Check the remaining budget.
4. Exit the program when done.

### Data Persistence:
- **Save Data**: The app allows saving the budget and expenses to a JSON file by using the `save_budget_data()` function.
- **Load Data**: You can load data from a previous session
