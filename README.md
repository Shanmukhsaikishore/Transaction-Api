# Transaction Management

## Overview
This project is focused on managing financial transactions efficiently and securely.

## Technologies Used
- Node.js
- Express.js
- sqlite3


## Features
- Add, update, and delete transactions
- View transaction history
- Generate financial reports

## API Endpoints

### Transactions
- `GET /api/transactions/{transaction_id}` - Retrieve a list of all transactions by transaction_id
- `POST /api/transactions` - Create a new transaction
- `GET /api/transactions?user_id=1` - Retrieve a specific transaction by user_id
- `PUT /api/transactions/{id}` - Update a specific transaction by ID

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/transaction-management.git
    ```
2. Navigate to the project directory:
    ```sh
    cd transaction-management
    ```
3. Install dependencies:
    ```sh
    npm install
    ```

## Usage
1. Start the application:
    ```sh
    npm start
    ```
2. Open your browser and navigate to `http://localhost:3000`
