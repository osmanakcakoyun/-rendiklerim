# uygulamalarım

class Matematik:
    def __init__(self, sayi1, sayi2):
    self.sayi1 = sayi1
    self.sayi2 = sayi2


def topla(self):
    return self.sayi1 + self.sayi2


def cikar(self):
    return self.sayi1 - self.sayi2


def carp(self):
    return self.sayi1 * self.sayi2


def bol(self):
    return self.sayi1 / self.sayi2


matematik = Matematik(2, 14)
matematik2 = Matematik(5, 7)
print("Toplam = " + str(matematik2.topla()))


# %% property

class Person:
    def __init__(self, firstName, lastName, age):
        self.firstName = firstName
        self.lastName = lastName
        self.age = age


person1 = Person("osman", "akçakoyun", 22)
print(person1.firstName)


class Worker(Person):
    def __init__(self, salary):
        self.salary = salary


class Customer(Person):
    def __init__(self, creditCardNumber):
        self.creditCardNumber = creditCardNumber


ahmet = Worker(3500)
mehmet = Customer(454215451214)
