# Simple Expense Tracker

This is a simple web-based expense tracker application that allows users to add transactions (income/expense), view their transaction history, and track their balance in real-time. The project is built using vanilla JavaScript, HTML, and CSS, and stores transactions locally in the browser using localStorage.

## Demo
![Screenshot of the Simple Expense Tracker](images/ss3.jpeg)

## Features
- *Add Transactions*: Users can add transactions by entering a description (text) and an amount. Positive values represent income, while negative values represent expenses.
- *Real-time Balance Update*: The app dynamically updates the balance, total income, and total expense based on the transactions added.
- *Transaction History*: Users can view their transaction history and delete any transaction if needed.
- *Local Storage*: Transactions are stored in the browser's localStorage, so they persist even when the page is refreshed or closed.
  
## Project Structure
- index.html: The main HTML file that sets up the structure of the webpage.
- style.css: The CSS file that provides the styling for the app's layout and design.
- script.js: The JavaScript file that contains the app's logic, including adding and removing transactions, calculating the balance, and interacting with local storage.

## Screenshots

### Transaction History
![Transaction History](images/ss4.jpeg)

## How It Works
1. The user inputs the transaction details (text and amount) in the form.
2. Upon submission, the transaction is added to the list, and the balance, income, and expenses are recalculated.
3. The transaction is saved to localStorage so that it persists across page reloads.
4. Users can delete transactions by clicking the 'x' button, which updates the balance and removes the item from localStorage.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/expense-tracker.git
