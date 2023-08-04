# PB This file defines a function called factorial() that calculates the factorial of a number. The print() statement at the end of the file prints the factorial of 10.

def factorial(n):
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

print(factorial(10))
