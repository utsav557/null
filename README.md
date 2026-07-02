# The Story Beiggin

""""
item = input("what item you like to buy ")
price = float(input("what is the price "))
quantity = int(input("how many you buy "))
total = price * quantity

print(total) """


# GAME

"""
djective1 = input("enter your edective1: ")
noun = input("enter your noun ")
adjective2 = input("enter your adjective2 ")

print(f"today i visit {djective1} cafee")
print(f"I shaw a biig {noun} in caffee")
print(f"a {noun} is very very {adjective2} therre") """


# Arithmetic

"""
friends = 2
friends += 1
print(friends)  """

"""
x = 142.54
y = 45
z = 14

result = round(x)
result = pow(4,3)
result = max(x,y,z)
result =(x,y,z)

print(result) """

"""
import math
radius = float(input("enter the radius of cricle"))

cri = 2 * math.pi * radius

print(F"this circuference is: {round(cri)} ")"""

"""
import math

radius = float(input("ENTER the radius of cricle"))

area = math.pi * pow(radius,2)
print(area)  """

"""
import math

a = float(input("disiced A:"))
b = float(input("disiced B:"))

c = math.sqrt(pow(a,2) + pow(b,2))

print(c)"""

# If statment
"""
age = int(input("Enter your age"))
if age >= 100:
    print("TOO OLd man")
elif age >= 18:
    print(f"your are big {age}") 
elif age < 1:
    print("enter correct age")
else:
    print(f"get out your ass {age}") """

"""
for_sale = False
if for_sale:
    print("this item is for sale")
else:
    print("nope") """

# CALCULATOR

"""
sign = input("enter your sign (+ - * /): ")

Num1 = float(input("enter your frist number "))
Num2 = float(input("enter your second number "))

if sign == "+":
    result = Num1 + Num2
elif sign == "-":
        result = Num1 - Num2
elif sign == "*":
      result = Num1 * Num2
elif sign == "/":
        result = Num1 / Num2
        print(result)
else:
       print(f"{sign} is not valid") """

# Weight Convert
"""
weight = float(input("ENter your weight: "))
Unit = input("Kilogram or Pound (K or P): ")

if Unit == "K":
    weight = weight * 2.205
    weight = "Lbs."

elif Unit == "P":
    weight = weight / 2.205
    print(weight)

else:
    print(f"{Unit} was not valid") """

# Temperature convert 
"""

unit = input("the temprechure is celius or fahrenhiet (C/F): ")
temp = float(input("enter the emprecher: "))

if unit == "C":
    temp = round((9 * temp) / 5 + 32)
    print(f"this tempreature in farhrenhiet is {temp} ")
elif unit == "F":
    temp = round((32 - temp) * 5/9 )
    print(f"this temreature in celcius is {temp}")
else:
    print(f"this {unit} is invalid") """

# Logical Oprators
"""
temp = 23

is_raining = False

if temp > 35 or temp < 0 or is_raining:
    print("not safe to go outside")
else:
    print("ALL CLEAR") """
"""
temp = -2
if_sunny = False

if temp >= 28 and if_sunny:
    print("its make you 🏴")

elif temp <= -1 and not if_sunny:
    print("its too cold or 🌥☁🌥")

else:
    print("all clear") """

# Strng method
"""
name = input("Enter your name: ")
phone_number = input("enter your phone number")

result = len(name)
result = name.find("a")
result = name.rfind("a")
result = name.capitalize()
result = name.upper()
result = name.isdigit()
result = name.isalph()
result = phone_number.count("7")
result = phone_number.replace("8" ,"2" )

print(result) """

# Some execrsize
"""
uname = input("Enter a name: ")
if len(uname) > 12:
    print("uname is to big")
elif uname.find(""):
    print("not allowed")
elif not uname.isalpha():
    print("its in alapha not allowed")
else:
    print("wellcome") """
