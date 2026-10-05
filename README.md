# Personal Expense Tracker (CLI)

## Project Description
This is a simple command-line Python application that helps users track their daily expenses.

Users can:
- Add new expenses
- View all expenses
- View total spending
- View spending by category
- Save expenses to a file

The data is stored locally in a JSON file.

---

## Project Structure

expense-tracker/
├─ src/
│ ├─ main.py
│ ├─ tracker.py
│ └─ storage.py
├─ data/
│ └─ expenses.json
├─ README.md
└─ .gitignore

---

## Setup Instructions

1. Create a virtual environment
python -m venv .venv

2. Activate the virtual environment

Windows
.venv\Scripts\activate

3. Installed required packages
pip install tabulate

----
## Run the application

Run the following command from the project folder:
python src/main.py


---

## Features

- Add expenses
- View expense list
- Total spending calculation
- Category summary
- Data stored using JSON


# Personal Expense Tracker (CLI)

## Features
- Add expenses (amount, category, description)
- View all expenses in a table
- Total spending
- Category summary
- Saves data to JSON and loads on restart

## Setup
1. Create & activate venv
2. Install dependencies:
   pip install tabulate

## Run
python src/main.py