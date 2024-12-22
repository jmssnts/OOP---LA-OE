#OE 6

class BankAccount:
    def __init__(self, account_number: str, balance: float):
        self._account_number = account_number
        self._balance = balance

    def deposit(self, amount: float):
        if amount > 0:
            self._balance += amount
            print(f"Deposited: {amount}")
        else:
            print("Deposit amount must be positive.")

    def withdraw(self, amount: float):
        if amount > 0:
            if amount <= self._balance:
                self._balance -= amount
                print(f"Withdrawn: {amount}")
            else:
                print("Insufficient funds.")
        else:
            print("Withdrawal amount must be positive.")

    def display_account_info(self):
        print(f"Account Number: {self._account_number}")
        print(f"Current Balance: {self._balance:.2f}")

    def __display_balance(self):
        print(f"Current Balance: {self._balance:.2f}")

    def get_account_number(self):
        return self._account_number

    def get_balance(self):
        return self._balance

    def set_balance(self, balance: float):
        if balance >= 0:
            self._balance = balance
        else:
            print("Balance cannot be negative.")

if __name__ == "__main__":
    account = BankAccount("987654321", 2500.0)
    print("Initial Account Info:")
    account.display_account_info()

    print("\nPerforming Transactions:")
    account.deposit(750.0)
    account.withdraw(500.0)
    account.set_balance(3000.0)

    print("\nFinal Account Info:")
    account.display_account_info()
