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
