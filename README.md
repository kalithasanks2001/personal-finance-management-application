**Personal Finance Management Application**

To help users manage their personal finances by tracking income, expenses, and generating financial reports. Built with Python and SQLite for data persistence.

**Project Overview**

This application allows users to:

1. Register and log in with unique credentials.
2. Add, update, and delete income and expense records.
3. Categorize transactions (e.g., Food, Rent, Salary).
4. Generate monthly and yearly financial reports.
5. Set budgets and receive alerts when budget limits are exceeded.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Features**

- **User Authentication**  
  Secure user registration and login system with SQLite.

- **Income and Expense Tracking**  
  Add, update, and delete income and expense entries with category tagging.

- **Financial Reports**  
  Generate detailed **monthly** and **yearly** reports, including:
  - Total Income
  - Total Expenses
  - Savings

- **Budget Management**  
  Set budgets for different categories and receive notifications when spending exceeds limits.

- **Data Persistence**  
  All data is securely stored using **SQLite**.

- **User-Friendly CLI**  
  The application is easy to use with clear instructions and a smooth workflow.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 **Technologies Used**

- **Programming Language**: Python  
- **Database**: SQLite3  
- **Libraries**: Pandas, SQLite3  

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Installation and Setup**

1. **Clone the repository**:
   git clone https://github.com/kalithasanks2001/personal-finance-management-application

2. **Install required libraries**:
   Ensure Python is installed on your system, then run:
   pip install pandas

3. **Run the application**:
   Launch the main script in your terminal:
   python finance_app.py

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**How to Use**

1. **Register a New User**  
   - Start the application.  
   - Choose the option to **Register** and provide a username and password.

2. **Login**  
   - Use your registered credentials to log in.

3. **Manage Transactions**  
   - Add income and expenses with categories like **Food, Rent, Salary, etc.**

4. **Generate Reports**  
   - View monthly or yearly reports to analyze your finances.

5. **Set Budgets**  
   - Set budget limits for expense categories and get alerts if limits are exceeded.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Testing**

To test the project, run the `unittest` suite:
python -m unittest finance_app_tests.py

The tests include:
- User registration
- User authentication
- Income and expense operations

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Project Structure**

finance-management-app/
│
├── finance_app.py            # Main application code
├── finance_app_tests.py      # Unit tests
├── finance.db                # SQLite database (generated automatically)
├── README.md                 # Project documentation
└── requirements.txt          # Project dependencies

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Future Enhancements**

- Add support for exporting reports as PDFs or Excel files.
- Include a GUI interface for a more user-friendly experience.
- Integrate notifications (email or SMS) for budget alerts.
- Add expense forecasting with machine learning.

-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x-x
