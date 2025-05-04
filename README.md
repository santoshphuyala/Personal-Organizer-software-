Personal Organizer
Overview
The Personal Organizer is a web-based application designed to help users manage their finances, tasks, and shopping lists efficiently. Built with HTML, CSS, and JavaScript, it features a user-friendly interface with a Dashboard, Expense Tracker, To-Do List, and Shopping List. The application uses localStorage for data persistence and supports data import/export in CSV and Excel formats, along with backup and restore functionality.
Features

Dashboard: Centralized overview with quick actions, financial summary, and recent activities.
Expense Tracker: Track expenses and income, set monthly budgets, and monitor balances.
To-Do List: Manage tasks with categories, priorities, reminders, and completion status.
Shopping List: Organize shopping items with categories, priorities, and expense integration.
Data Management: Import/export data in CSV/Excel, backup/restore in JSON, and clear all data.
Responsive Design: Optimized for both desktop and mobile devices.

Prerequisites

A modern web browser (e.g., Chrome, Firefox, Edge).
No server-side dependencies; runs entirely in the browser.
Optional: Internet access for loading the XLSX library from CDN.

Installation

Clone or Download:

Clone the repository or download the project files.
Ensure dashboard.html is included in the project directory.


Serve the Application:

Open dashboard.html directly in a web browser by double-clicking the file, or
Use a local web server (e.g., python -m http.server 8000 or VS Code Live Server) to serve the file for a better experience.


Dependencies:

The application includes the XLSX library via CDN (https://cdnjs.cloudflare.com/ajax/libs/xlsx/0.18.5/xlsx.full.min.js) for Excel import/export. No additional setup is required.



Usage

Open dashboard.html in your browser.
Use the top tabs or sidebar menu to navigate between Dashboard, Expense Tracker, To-Do List, and Shopping List.
Interact with each section to add, edit, or delete items, set budgets, or manage tasks and shopping lists.
Use the Import/Export dropdowns to manage data or the "Clear All Data" button to reset the application.

Project Structure

dashboard.html: The main application file containing HTML, CSS, and JavaScript.
No additional files are required for basic functionality.

Contributing
Contributions are welcome! To contribute:

Fork the repository.
Create a feature branch (git checkout -b feature/your-feature).
Commit changes (git commit -m 'Add your feature').
Push to the branch (git push origin feature/your-feature).
Open a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.
Author
Designed and developed by Santosh Phuyal.
