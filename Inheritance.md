#Single

class Father:
 def house(self):
 print("Father has a house")

class Son(Father):
    def bike(self):
        print("Son has a bike")

s = Son()
s.house()
s.bike()


#Multiple Inheritance

class Father:
    def money(self):
        print("Father has money")

class Mother:
    def gold(self):
        print("Mother has gold")

class Son(Father, Mother):
    def bike(self):
        print("Son has a bike")

s = Son()
s.money()
s.gold()
s.bike()

#Multilevel Inheritance
class Grandfather:
    def house(self):
        print("Grandfather has a house")

class Father(Grandfather):
    def car(self):
        print("Father has a car")

class Son(Father):
    def bike(self):
        print("Son has a bike")

s = Son()
s.house()
s.car()
s.bike()

#Hierarchical Inheritance

class Father:
    def house(self):
        print("Father has a house")

class Son(Father):
    def bike(self):
        print("Son has a bike")

class Daughter(Father):
    def car(self):
        print("Daughter has a car")

s = Son()
s.house()
s.bike()

d = Daughter()
d.house()
d.car()

#Hybrid Inheritance
class A:
    def show(self):
        print("Class A")

class B(A):
    def display(self):
        print("Class B")

class C(A):
    def print_data(self):
        print("Class C")

class D(B, C):
    def result(self):
        print("Class D")

obj = D()
obj.show()
obj.display()
obj.print_data()
obj.result()
