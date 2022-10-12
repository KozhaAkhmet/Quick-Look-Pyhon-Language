# Quick-Look-Pyhon-Language 
 This repository is for programmers who switch from another language or struggle with python syntax.

#
```py

# Many of this examples are from https://www.pythontutorial.net/python-basics/python-string/ 

# ============================================ SYNTAX AND VARIABLES ===========================================

# Variable names cannot contain spaces. To separate words in variables, you use underscores for example sorted_list.

greeting = 'Good '
time = 'Afternoon'

greeting = greeting + time + '!'
print(greeting)

# ----------------------------

str = "Python String"
print(str[0]) # P
print(str[1]) # y

# ----------------------------

s = 'This is a string'
print(s)
s = "Another string using double quotes"
print(s)
s = ''' string can span
        multiple line '''
print(s)

# ----------------------------

str = "Python String"
print(str[-1])  # g
print(str[-2])  # n

# ----------------------------

# The str[0:2] returns a substring that includes the character from the index 0 (included) to 2 (excluded).
# Example: string[start:end] 

str = "Python String"
print(str[0:2]) 

# Output: 
# Py

# ----------------------------

# Python strings are immutable*****

str = "Python String"
str[0] = 'J' 

# Ouput:
# Traceback (most recent call last):
#   File "app.py", line 2, in <module>
#     str[0] = 'J'
# TypeError: 'str' object does not support item assignment</module>

# ----------------------------

count = 10000000000
# Can also implemented as:
count = 10_000_000_000

# ----------------------------

# The bool() function
>>> bool('Hi')
True
>>> bool('')
False
>>> bool(100)
True
>>> bool(0)
False

# ----------------------------

# Python multiline comments
def increase(salary, percentage, rating):
    """ increase salary base on rating and percentage
    rating 1 - 2 no increase
    rating 3 - 4 increase 5%
    rating 4 - 6 increase 10%
    """

# ----------------------------

# the input() function returns a string, not an integer.

price = input('Enter the price ($):')
tax = input('Enter the tax rate (%):')

# To convert a string to a number, you use the int() function. More precisely, the int() function converts a string to an integer.
net_price = int(price) * int(tax) / 100 
print(f'The net price is ${net_price}')

# ----------------------------

# shows the ticket price
print(f"You'll pay ${ticket_price} for the ticket")

# ----------------------------

# Getting the type of a value
>>> type(100)
<class 'int'>

>>> type(2.0)
<class 'float'>

>>> type('Hello')
<class 'str'>

>>> type(True)
<class 'bool'>

# ========================================= IF SATMENTS AND LOGIC CONDITIONS =========================================

# The if...else statement:
age = input('Enter your age:')
if int(age) >= 18:
    print("You're eligible to vote.")
else:
    print("You're not eligible to vote.")

# ----------------------------

# the if...elif...else statement:

age = input('Enter your age:')

# convert the string to int
your_age = int(age)

# determine the ticket price
if your_age < 5:
    ticket_price = 5
elif your_age < 16:
    ticket_price = 10
else:
    ticket_price = 18

# -----------------------------

# Alternative if...else
ticket_price = 20 if int(age) >= 18 else 5

# -----------------------------

# Backslash (\) character to continue a statement in the second line:

if (a == True) and (b == False) and \
   (c == True):
    print("Continuation of statements")

# ================================================ FUNCTIONS ========================================================
# Declaring function
def function(state):
    if(state):
    # Function code

# Declaring function with return value
def function_with_return():
    if(True):
    # Function code
```
