# Programming Principles and Concepts in Python

## 1. Inheritance:

### Overview:
Inheritance is a core principle of object-oriented programming (OOP) where a class (subclass) can inherit attributes and methods from another class (superclass). This promotes code reusability and establishes a hierarchy among classes.

### Commentary:
Inheritance facilitates the creation of specialized classes that inherit common functionalities from a base class. It allows for code organization, promotes polymorphism, and enables easier maintenance and extension of codebases.

### Example:
```python
class Animal:
    def sound(self):
        print("Animal makes a sound")

class Dog(Animal):
    def sound(self):
        print("Dog barks")

dog = Dog()
dog.sound()  # Output: Dog barks
