1. Objectives

To develop a simple Personal Expense Calculator using HTML, CSS, and JavaScript.

To allow users to enter their monthly income and expenses.

To categorize expenses such as food, transport, education, shopping, and entertainment.

To automatically calculate the total expenses.

To calculate the user's remaining savings after expenses.

To display expenses in an organized table format.

To generate a category-wise expense summary.

To practice JavaScript variables, functions, calculations, DOM manipulation, and event handling.

To create a simple and user-friendly interface for managing personal finances.


2. Tools and Techniques:

Tool / Technology	Purpose

HTML5	Creates the structure of the expense calculator

CSS3	Provides styling and layout

JavaScript	Implements calculations and functionality

VS Code	Used for developing the application

HTML Input	Accepts income, expense name, and amount

HTML Select	Allows users to select expense categories

JavaScript Functions	Handles adding expenses

DOM Manipulation	Updates the table and summary dynamically

Template Literals	Dynamically creates expense table rows

Objects	Stores category-wise expense totals

Arithmetic Operations	Calculates expenses and savings

3. Features:

1. Income Input:

The user can enter their total income.

Example:

Income: ₹20,000

2. Expense Entry:

Users can enter:

Expense name

Expense amount

Expense category


3. Expense Categories:

The application provides categories such as:

Food

Transport

Education

Shopping

Entertainment

Other

4. Add Expense:

The Add Expense button adds the entered expense to the expense table.

5. Expense Table:

All added expenses are displayed in a table containing:

Expense	Category	Amount

Food	Food	₹500
Bus	Transport	₹300
Books	Education	₹1,000


6. Total Expense Calculation:

The application automatically calculates the total amount spent.

7. Savings Calculation:

Savings are calculated using:

Savings = Total Income − Total Expenses

8. Category-wise Summary:

The application displays the total amount spent in each category.

Example:

Food: ₹1500
Transport: ₹800
Education: ₹2000
Shopping: ₹1000

9. Input Validation:

If the user doesn't enter an expense name or enters an invalid amount, an alert is displayed:

Enter expense details

10. Automatic Form Clearing:

After an expense is successfully added, the expense name and amount fields are automatically cleared.

4. Output:

The final application appears similar to:

┌───────────────────────────────────┐
│     Personal Expense Calculator   │
│                                   │
│ [ Enter Income ₹              ]   │
│ [ Expense Name                ]   │
│ [ Expense Amount ₹            ]   │
│                                   │
│ [ Food                      ▼ ]   │
│                                   │
│       [ Add Expense ]             │
│                                   │
│ ┌─────────┬───────────┬────────┐  │
│ │ Expense │ Category  │ Amount │  │
│ ├─────────┼───────────┼────────┤  │
│ │ Food    │ Food      │ ₹500   │  │
│ │ Bus     │ Transport │ ₹300   │  │
│ │ Books   │ Education │ ₹1000  │  │
│ └─────────┴───────────┴────────┘  │
│                                   │
│          Summary Report           │
│                                   │
│ Total Income:   ₹20,000           │
│ Total Expenses: ₹1,800            │
│ Savings:        ₹18,200           │
│                                   │
│ Food: ₹500                        │
│ Transport: ₹300                   │
│ Education: ₹1,000                 │
└───────────────────────────────────┘

Expected Result:

The Personal Expense Calculator successfully records expenses, calculates total expenses and savings, and provides a category-wise spending summary. The project demonstrates practical use of HTML forms, CSS styling, JavaScript calculations, DOM manipulation, objects, functions, and event handling.
