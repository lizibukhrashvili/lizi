# lizi
Homework_3

# დავალება N1
class celsius:
    def __init__(self):
        


# დავალება N2
class bank_account:
    def __init__(self, account_name, __balance=0):
        self.__account_name = account_name
        self.__balance = __balance
    def get_account_name(self):
        return self.__account_name
    def __str__(self, account_name):
        self.__account_name = account_name
    def _str__(self):
        return f"გამარჯობა ლიზი: {self.__account_name}, თქვენ ანგარიშზე გაქვთ: {self.__balance} ლარი"
    def deposit(self, amount):
        self.__balance += amount
        print(f"თანხის შეტანა შესრულებულია, ამჟამად თქვენ ანგარიშზე გაქვთ:{self.__balance} ლარი")
    def withdraw(self, amount):
        self.__balance += amount
        print(f"თანხის გამოტანა შესრულებულია, ამჟამად თქვენ ანგარიშზე გაქვთ: {self.__balance} ლარი")


name_ = bank_account("ლიზი", "ბუხრაშვილი", "120")
name_.deposit(bank_account, 50)
name_.withdraw(bank_account, 20)
print(name_)


# დავალება N3
class point:
    def __init__(self, x, y):
        self.x = x
        self.y = y


point_1 = point(3, 5)
point_2 = point(6, 9)
