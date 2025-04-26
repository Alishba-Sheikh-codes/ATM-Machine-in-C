# 💳 ATM Machine Simulation

## 📜 Description
This project is a simple **ATM Machine Simulation** created using **C programming language**.  
It simulates basic ATM functionalities such as:

- PIN authentication
- Checking balance
- Depositing amount
- Withdrawing amount
- Exiting the application

It also provides **colorful output** for a better user experience!

---

## 🚀 Features
- 4-digit secure PIN verification (with maximum 3 attempts).
- Check current balance.
- Deposit money (positive amounts only).
- Withdraw money (only if sufficient balance is available).
- Graceful exit with thank-you messages.
- Error handling for invalid inputs.

---

## 🛠️ How to Run
1. Save the code file as `atm_simulation.c`.
2. Compile the program using a C compiler:
gcc atm_simulation.c -o atm_simulation
3. Run the compiled program:
./atm_simulation

## 📋 Default Settings
- Default PIN: `2346`
- Initial Balance: `1,000,000`

---

## 🎨 Program Flow
- User is asked to enter a 4-digit PIN.
- If PIN is correct:
- Options are shown: Check Balance, Deposit, Withdraw, Quit.
- If PIN is incorrect:
- User has 3 attempts before getting locked out.

---

## 💡 Example Output
******** WELCOME TO THE ATM ********
Please enter your 4-digit PIN: 2346

ACCESS GRANTED!

Available Transactions:

Check Balance

Deposit Amount

Withdraw Amount

Quit Application


## 👨‍💻 Author
- Alishba Saleem


## ⚡ Note
- This is a beginner-level project for practicing basic C concepts like conditionals, loops, and user input handling.