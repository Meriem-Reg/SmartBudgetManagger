# SmartBudgetManagger
A project for managing Budget.

## What is it?

SmartBudget Manager is a simple Excel workbook to follow your **monthly income and expenses**. You type your transactions, and the workbook calculates your balance, compares your spending with your budget and draws a **pie chart** by category. It warns you in **red** when you go over budget.

## What do I need?

* Microsoft Excel 2016, 2019, 2021 or Microsoft 365 (or a compatible program such as LibreOffice Calc)
* The file `SmartBudget\_Manager.xlsx`
* Basic skills: open a file, click a cell, type a number, save

## Files in this package

|File|Content|
|-|-|
|`SmartBudget Manager.xlsx`|The workbook|
|`SmartBudget User Guide.pdf`|Step-by-step user guide|
|`Software Requirements.docx`|What the workbook must do|

## The three worksheets

|Sheet|Use|
|-|-|
|**Dashboard**|Read your balance, budget status and chart. Do not type here.|
|**Transactions**|Enter every income and expense.|
|**Categories**|See the categories and change each monthly budget.|

## Quick start

1. Open `SmartBudget\_Manager.xlsx`. If Excel shows a yellow bar, click **Enable Editing**.
2. Go to the **Transactions** tab (bottom of the window).
3. In the first empty row, enter a **Date** and a **Description**.
4. Choose **Income** or **Expense** in the **Type** list, then choose a **Category** for an expense.
5. Type the amount in the **Income** *or* the **Expense** column (not both). Press **Enter**.
6. Open the **Dashboard** tab: the totals, the status and the chart have updated.

## Important rules

* Do **not** type in the **Month** column or in the Dashboard: they are formulas.
* Use the drop-down lists; do not type a category by hand.
* Only rows **4 to 50** are counted.
* The status turns **red – OVER BUDGET** when total expenses are higher than the total budget.

## Known limitations

Five categories only on the Dashboard; all months are added together (use one file per month); no password by default.

## Help

Contact: support@gmail.com
