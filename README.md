🎯 Project Overview
The goal of this project is to create a simple, yet effective, terminal-based application where users can input their daily expenses, categorize them, and receive insights on their spending habits. The app saves each expense entry to a CSV file and summarizes the total expenditures for the month, helping users manage their budget.

✅ Features

Expense Input: Users can add an expense by entering the name, category, and amount directly into the terminal.

CSV Storage: All expenses are saved in a .csv file for easy access and future reference.

Expense Summary: The app reads the saved expenses and provides a summary of the total expenses for the month.

Budget Tracking: The app shows users how much they can spend for the rest of the month to stay within a pre-defined budget.
✨ Bonus Features

Category-wise Summary: View expenses by category to understand where most of your money is going.

Daily Budget Estimate: Get a rough estimate of how much you have left to spend per day to stay within your budget.

💡 Project Structure

The project is organized into two main files:

expense.py: Contains the Expense class for creating and managing expense objects.

expense_tracker.py: The main application file containing the logic for expense input, saving, and summarization.

🧩 Example Usage

Here’s a brief example of how the app works:

🎯 Running Expense Tracker!

🎯 Getting User Expense

Enter expense name: coffee

Enter expense amount: 5
Select a category: 
  1. 🍔 Food
  2. 🏠 Home
  3. 💼 Work
  4. 🎉 Fun
  5. ✨ Misc

Enter a category number [1 - 5]: 1

🎯 Saving User Expense: <Expense: coffee, 🍔 Food, $5.00 > to expenses.csv

🎯 Summarizing User Expense

Expenses By Category 📈:
 
  🍔 Food: ₹5.00

💵 Total Spent: ₹5.00

✅ Budget Remaining: ₹1995.00

👉 Budget Per Day: ₹66.50

📊 CSV Integration

The generated CSV file can be easily imported into spreadsheet applications like Excel or Google Sheets, allowing for further analysis and visualization.!

📸 Screenshots

Here are some example screenshots of the app:[Screenshot 2024-08-15 105050](https://github.com/user-attachments/assets/48e5caac-0d44-4284-818a-394c0107401c)
