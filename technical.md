# Technical Report

## 1. What is a class object in Python?
In Python, a class object is a blueprint for creating instances (objects). It defines characteristics (attributes) and methods that can be used by the objects created from it.

## 2. What is a docstring?
Docstring are string literals that document a function, class, or module and usually are enclosed in triple quotes (`""" or '''`). Its function is to help describe the purpose of the code.

## 3. How to define `__init__` in a class object?
The `__init__` method is a special method in Python classes that acts as a constructor. It initializes an instance of the class. Example:


class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age


## 4. How do you let functions fail gracefully?
To let functions fail gracefully, we use try-except blocks to prevent the program from crashing when an error occurs. Instead, the error is caught, and a message can be displayed or logged.

Code Example:



try:
    result = 10 / 0
except ZeroDivisionError:
    print("Cannot divide by zero!")



## 5. What’s a standard practice of a return statement?
A return statement is used in functions to send back a result instead of printing it. A good practice is to return meaningful values rather than having functions print directly, making the function more reusable.

def add(a, b):
    return a + b




