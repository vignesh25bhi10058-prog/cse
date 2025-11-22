# cse
Smart Personal Expense Tracker

A minimal "smart" personal expense tracker built with Python and Streamlit. It helps you track your daily spending and income with automatic category suggestions, budget alerts, and interactive visualizations.

Features

Secure & Private
User Authentication: Secure Login and Registration system.
Data Privacy: Each user has their own private data and settings.

Complete Financial Tracking
Income & Expenses: Track your salary, freelance income, and all your daily expenses.
Smart Categorization: Automatically suggests categories based on item names (e.g., "Uber" -> "Transport").

Budget Enforcer
Set Limits: Define monthly budgets for specific categories (e.g., 200 dollors for Food).
Realtime Alerts: Get visual warnings when you are nearing or exceeding your budget.

interactive Dashboard
Net Balance: See your total Income vs. Expenses at a glance.
Trend Analysis: Compare Income and Expenses over time.
Category Breakdown: Interactive pie charts showing where your money goes.

How to Run:

Option 1: The Easy Way (Windows)
Double-click the 'run_app.bat' file in this folder. It will automatically:
1.Install all dependencies (including security libraries).
2.Launch the application.

Option 2: Manual Setup
1.Install Dependencies:
 bash
    pip install -r expense_tracker/requirements.txt
    

2.Run the App:
    bash
    streamlit run expense_tracker/app.py
    

Project Structure
expense_tracker
    app.py              # Main Streamlit application
    requirements.txt    # Project dependencies
    data/
    expenses.db         # SQLite database
src
    auth.py             # User authentication & hashing
    budget.py           # Budget management logic
    crud.py             # Transaction operations
    db.py               # Database connection & schema
    analytics.py        # Visualization logic
    utils.py            #Helper functions


Technologies()
               (streamlit)(https://streamlit.io/)
Backend: Python
Database: SQLite
Security: Bcrypt (Password)
Visualization: Plotly
