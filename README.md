# Account-balance-Function

def check_balance():
    return f"Your current balance is: balance:.2f"

def deposit(amount):
    global balance
    if amount > 0:
        balance += amount
        return f"Deposited:{amount:.2f}check_balance()"
    else:
        return "Invalid deposit amount."
def withdraw(amount):
    global balance
    if 0 < amount <= balance:
        balance -= amount
        return f"Withdrew: ${amount:.2f}check_balance()"
    else:
        return "Insufficient balance or invalid amount."
