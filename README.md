# Expense-Tracking-React

Welcome to the Expense-Tracking-React project! This application helps you manage your expenses by providing an intuitive user interface to display and track transactions, as well as showing your overall balance, total expenses, and income. You can also add new transactions and delete existing ones.

## Features
![Home page](/src/assets/Home.png)

- **Create UI for Project Display**: A user-friendly interface for displaying your expense tracking information.
- **Transaction Items**: View and manage individual transaction items.
- **Show Balance, Expense, and Income Totals**: Instantly see your financial summary.
- **Add New Transaction and Reflect in Total**: Easily add new transactions and see the changes in your totals in real-time.
- **Delete Items**: Remove transactions as needed and update the totals accordingly.

## Technologies Used

- **React JS**: A JavaScript library for building user interfaces.
- **Pure CSS**: Simple and efficient styling without additional libraries.
- **useContext Hook**: A React Hook for managing and passing state globally across the application.

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- Node.js (https://nodejs.org/)
- npm (https://www.npmjs.com/)

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Meanhor/Expense-Tracking-React.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Expense-Tracking-React
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

### Running the Application

1. To start the development server, run:
```
npm dev run
```
2. open http://localhost:####/ (depend on your device) to view it in the browser

## Key Components
- **AddTransaction.jsx**: Form to add new transactions.
- **Balance.jsx**: Displays the current balance.
- **Header.jsx**: Header component of the application.
- **IncomeExpenses.jsx**: Shows the total income and expenses.
- **Transaction.jsx**: Individual transaction item component.
- **TransactionList.jsx**: Lists all transactions.

## Context and State Management

### GlobalState.js

Provides global state using `useContext` and `useReducer` for managing transactions.

### AppReducer.js

Reducer function to handle actions related to transactions.


## Technologies Used
Distributed under the MIT License. See LICENSE for more information.

## Contact

Project Link: [https://github.com/Meanhor/Expense-Tracking-React.git](https://github.com/Meanhor/Expense-Tracking-React.git)

## Acknowledgments

- [Vite](https://vitejs.dev/) - For fast and optimized development.
- [React](https://reactjs.org/) - For building the user interface.