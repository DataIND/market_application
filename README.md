# Flask E-Commerce Application

This is a Flask-based web application that allows users to buy and sell products. The application features user authentication, wallet management, and secure password storage.

## Features

- **User Registration and Login**: Users can create an account and log in to access their dashboard.
- **Product Transactions**: Users can buy and sell products, with transactions tracked separately for each user.
- **Wallet Management**: Users can view their wallet balance, which updates after each transaction. Purchases are restricted if the user has insufficient funds.
- **Secure Password Storage**: User passwords are encrypted using Bcrypt before being stored in the database.

## Technologies Used

- **Flask**: A lightweight WSGI web application framework.
- **Flask-Login**: For user session management.
- **Flask-SQLAlchemy**: For database interactions.
- **Flask-Bcrypt**: For password hashing.
- **WTForms**: For form handling and validation.

## Usage
- Navigate to the login page to access your account or register a new account.
- Once logged in, you can view your wallet balance and perform buy/sell transactions.
  
## Code Overview
The main components of the application include:
- **User Authentication**: Handled by Flask-Login, allowing users to log in and out securely.
- **Database Models**: Defined using Flask-SQLAlchemy to manage user data and transactions.
- **Forms**: Created using WTForms for user input, with validation to ensure data integrity.
