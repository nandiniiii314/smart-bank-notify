# smart-bank-notify
# 🏦 Bank Account Transaction System with SMS Alerts 📲

A simple Python bank account system that supports deposits and withdrawals, sends SMS notifications via Twilio, and logs all transactions.

---

## ✨ Features

- 💸 Deposit and withdraw money with validation  
- 📩 SMS alerts for every transaction via Twilio  
- ⚠️ Custom exception handling (`InvalidAccountError`)  
- 📝 Transaction and error logging to a file  
- 🖥️ Simple command-line interface for user input


🔮 Future Enhancements
-Add transfer functionality between accounts

-Persist account data in a database or file

-Implement unit tests

-Build a GUI interface

-Add Docker support


⚠️ Error Handling
-Withdrawals exceeding balance raise InvalidAccountError

-Deposits with zero or negative amounts raise InvalidAccountError

-Errors trigger SMS notifications and log warnings




