# Finane Tracker 2.0 Application - README

## Overview
The **Finane Tracker 2.0Expense Tracker Application** is a graphical tool designed to simplify managing and analyzing your personal finances. With this application, you can record daily expenses, generate insightful reports, and visualize financial data. The application uses an intuitive GUI and stores your data in an SQLite3 database.

---

## Features
- **Add, Delete, Update and View Expenses**: Record your expenses with details such as date, category, and amount.
- **Generate Reports**:
  - Monthly summary of expenses.
  - Category-wise breakdown.
  - Detailed reports for custom date ranges.
- **Export Data**: Save your expense data in CSV format for external use or sharing.
- **Import Data**: Enable users to import expense data from CSV files for easy integration with external sources or sharing.
- **Visualizations**:
  - **Bar Charts**: Monthly spending trends.
  - **Pie Charts**: Category-wise spending distribution.
- **Spending Insights**: Recommendations to optimize your expenses.

---

## Installation

### Dependencies
Ensure the following Python libraries are installed:

- `sqlite3`: Built-in Python library for database management.
- `csv`: Built-in Python library for working with CSV files.
- `datetime`: Built-in Python library for date and time operations.
- `tkinter`: Built-in Python library for GUI applications.
- `pandas`: For data analysis and manipulation.
- `Django`: Web framework used for developing the Finance Tracker application.
- `Plotly`: Used for creating interactive visualizations, including bar and pie charts.
- `NumPy`: For numerical operations, supporting data analysis in visualizations.
- `Django` HTMX: For handling dynamic updates in the user interface without page reloads.

### Installation Steps
1. Clone the repository or download the script file:
   ```bash
   git clone https://github.com/your-repo/expense-tracker.git](https://github.com/GorBarkhudarian/FinanceTracker2.0)
   cd Django-HTMX-Finance-App
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt 
   ```

---

## Usage

1. Run the script:
   ```bash
    python manage.py runserver
   ```
2. Use the GUI to:
   - **Add Expenses**: Fill in the date, category, and amount fields, then click "Add Expense."
   - **Delete Expenses**: Select one or multiple rows in the expense list and click "Delete Expense."
   - **Update Expenses**: Select one or multiple rows in the expense list and click "Update Expense."
   - **View Reports**: Use the calendar to set a date range and click "Generate Report."
   - **Export Data**: Click "Export to CSV" to save your expenses as a CSV file.
   - **Visualize Data**: Click "Show Spending Chart" or "Show Category Pie Chart."

---

## Database
- The application uses an SQLite database (`expenses.db`) to store expense records.
- Table schema:
  - `id`: Auto-incrementing primary key.
  - `date`: Date of the expense (YYYY-MM-DD).
  - `category`: Category of the expense (e.g., Food, Transportation).
  - `amount`: Expense amount (positive number).

---

## Files and Folders
- **`expenses.py`**: The main script file for the application.
- **`expenses.db`**: SQLite database file (created automatically on first run).
- **`README.md`**: Documentation for the application.

---

## Recommendations
The application provides recommendations to help you save money by analyzing spending patterns. For example:
- Reduce spending on dining out if it exceeds 20% of your total expenses.
- Cut down on entertainment expenses if they exceed 15% of your total expenses.

---

## Author
- **Gor Barkhudaryan**
