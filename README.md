# Personal Finance Tracker: Analyzing My Own Finances

This project is a personal finance analysis I conducted to better understand my spending, saving, and income patterns.

**Goals of this project:**
- Track income and expenses over several months.
- Identify patterns in spending habits.
- Visualize and compare financial trends.
- Improve decision-making and budgeting in the future.

## Data Loading & Cleaning

The dataset was manually tracked and includes:
- `Date`: When the transaction occurred
- `Description`: Short note about the transaction
- `Category`: Income, Rent, Food, etc.
- `Expense` and `Income`: Separated columns
- Derived fields like: `Month`, `Day of Week`, `Running Totals`, etc.

**Cleaning steps:**
- Parsed the `Date` column to datetime format
- Filtered and separated income from expenses
- Added calculated columns for `Running Total`, `Half of Month`, and `Savings`
