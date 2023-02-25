The Bankist Bank App is a simple banking application that allows users to perform various operations like logging in, transferring money, requesting loans, and closing their accounts.

Let's start with a breakdown of the data structure used in the application:

# Data

- The accounts array contains four objects representing different bank accounts.
- Each account object contains the following properties:
  - owner: The account owner's name.
  - movements: An array of numbers representing the transactions made on the account.
  - interestRate: The annual interest rate of the account in percentage.
  - pin: The account's four-digit pin number.

# Elements

- The application contains various elements that are used to display information to the user and take inputs from the user.
- These elements are selected using DOM manipulation and stored in variables:
  - labelWelcome: The welcome message displayed to the user upon successful login.
  - labelDate: The date and time displayed in the application.
  - labelBalance: The current balance of the logged-in user's account.
  - labelSumIn: The total amount of money deposited into the logged-in user's account.
  - labelSumOut: The total amount of money withdrawn from the logged-in user's account.
  - labelSumInterest: The total amount of interest earned by the logged-in user's account.
  - labelTimer: A timer element that is not used in this implementation.
  - containerApp: The main application container.
  - containerMovements: The container that displays the transaction history of the logged-in user's account.
  - btnLogin: The login button.
  - btnTransfer: The button used to transfer money to other accounts.
  - btnLoan: The button used to request a loan from the bank.
  - btnClose: The button used to close the logged-in user's account.
  - btnSort: The button used to sort the transaction history by amount.
  - inputLoginUsername: The input field for the user's username during login.
  - inputLoginPin: The input field for the user's pin during login.
  - inputTransferTo: The input field for the recipient's account number during money transfer.
  - inputTransferAmount: The input field for the amount to transfer during money transfer.
  - inputLoanAmount: The input field for the loan amount to request.
  - inputCloseUsername: The input field for the username of the account to be closed.
  - inputClosePin: The input field for the pin of the account to be closed.

# Functions

The application has several functions that perform different tasks:

- displayMovements: This function takes an array of transactions as input and displays them in the transaction history container. It can also sort the transactions by amount if the sort parameter is set to 'true'.
- calcDisplayBalance: This function calculates and displays the current balance of the logged-in user's account.
- calcDisplaySummary: This function calculates and displays the total amount of money deposited, withdrawn, and earned as interest by the logged-in user's account.
- createUsernames: This function creates a username for each account based on the owner's name.
- updateUI: This function updates the UI with the latest account information after a successful login or any other operation that changes the account data.

# Event Handlers

- btnLogin event listener: This event listener listens for clicks on the login button. Upon a successful login, it updates the UI to display the user's account information and transaction history.
- btnTransfer event

# testing
users = [
{username: as,
password: 1111
},
{username: jd,
password: 2222
},
{username: stw,
password: 3333
},
{username: sm,
password: 4444
},
]
- You can transfer between users