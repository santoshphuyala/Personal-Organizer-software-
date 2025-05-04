Personal Organizer User Guide
Introduction
The Personal Organizer is a web-based tool to manage your finances, tasks, and shopping lists. This guide provides detailed instructions on how to use each feature, including the Dashboard, Expense Tracker, To-Do List, and Shopping List.
Getting Started

Open the Application:

Open dashboard.html in a web browser (e.g., Chrome, Firefox).
No internet is required except for the initial load of the XLSX library for import/export features.


Navigation:

Use the top tabs (Dashboard, Expense Tracker, To-Do List, Shopping List) to switch between sections.
Click the hamburger menu (☰) in the top-left corner to open the sidebar for navigation or to clear all data.



Dashboard
The Dashboard provides a centralized overview of your activities.

Quick Actions:

Click buttons to navigate to forms for adding expenses, income, tasks, or shopping items.


Summary:

View total expenses, total income, balance, pending tasks, and pending shopping items.


Recent Activities:

See the 5 most recent actions (e.g., expenses added, tasks completed) with details like date and status.



Expense Tracker
Manage your finances by tracking expenses, income, and budgets.
Adding/Editing Expenses or Income

Navigate to the Expense Tracker tab.
In the Add/Edit Expense or Add/Edit Income section:
Enter a description, amount, and date.
Click Add Expense or Add Income to save.
To edit, click Edit on an existing item, update the fields, and click Update Expense or Update Income.



Setting a Budget

In the Set Monthly Budget section, enter a budget amount (in NRs).
Click Set Budget to save.
Alerts appear if expenses exceed 90% or 100% of the budget.

Filtering and Sorting

Search: Enter text in the search bar to filter by description.
Filter: Select "All," "Expenses," or "Income" from the dropdown.
Sort: Click Sort by Date to toggle between ascending and descending order.

Deleting Items

Click Delete next to an expense or income item to remove it.

Import/Export

Click the Import/Export dropdown.
Choose:
Export to CSV/Excel: Download data as a CSV or Excel file.
Import from CSV: Upload a CSV file with headers (Type,Description,Amount,Date).
Backup: Save data as a JSON file.
Restore: Upload a JSON backup to restore data.



To-Do List
Organize tasks with categories, priorities, and reminders.
Adding/Editing Tasks

Navigate to the To-Do List tab.
Enter task details:
Task description, date, optional reminder (date and time), category (Personal, Work, Urgent), priority (Low, Medium, High), and completion status.


Click Add Task to save or Update Task to edit an existing task.
To edit, click Edit on a task, update fields, and save.

Managing Tasks

Complete/Incomplete: Check/uncheck the box to toggle completion status.
Add to Shopping List: Click Add to Shopping on a completed task to move it to the Shopping List.
Delete: Click Delete to remove a task.

Reminders

Set a reminder date and time when adding/editing a task.
Notifications appear 5 minutes before and at the reminder time (browser notifications must be enabled).

Filtering and Sorting

Search: Filter tasks by description.
Filter: Select by category, priority, or completion status.
Sort: Toggle date sorting with Sort by Date.

Import/Export

Use the Import/Export dropdown to export tasks to CSV/Excel, import from CSV (Task,Completed,Date,Reminder,Category,Priority), or backup/restore as JSON.

Shopping List
Manage shopping items with categories and priorities, integrated with expenses.
Adding/Editing Items

Navigate to the Shopping List tab.
Enter item details: name, date, category, and priority.
Click Add Item or Update Item to save.
To edit, click Edit, update fields, and save.

Managing Items

Complete/Incomplete: Check the box to mark as completed (prompts for a price to add to expenses) or uncheck to mark as incomplete.
Delete: Click Delete to remove an item.

Filtering and Sorting

Search: Filter by item name.
Filter: Select by category, priority, or completion status.
Sort: Toggle date sorting with Sort by Date.

Import/Export

Use the Import/Export dropdown to export to CSV/Excel, import from CSV (Item,Date,Completed,Category,Priority), or backup/restore as JSON.

Data Management

Clear All Data: In the sidebar, click Clear All Data and confirm to reset the application.
Data Persistence: All data is saved in the browser's localStorage and persists across sessions.

Troubleshooting

Notifications Not Working: Ensure browser notifications are enabled for the site.
Import Errors: Verify CSV files have the correct headers and data formats.
Data Not Saving: Check browser storage limits or clear localStorage via developer tools.
Excel Export Issues: Ensure the XLSX library CDN is accessible.

Support
For issues or feature requests, contact the developer or submit a GitHub issue (if hosted on GitHub).
Author
Designed and developed by Santosh Phuyal.
