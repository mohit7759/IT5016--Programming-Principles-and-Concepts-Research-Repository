# Programming Principles and Concepts in Python

## Inheritance:

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
```
## Function:

### Overview:
Functions are blocks of organized, reusable code designed to perform a specific task. They help in modularizing code, promoting code reuse, and enhancing readability.

### Commentary:
Functions in Python follow a "def" keyword followed by a function name and parameters enclosed within parentheses. They encapsulate logic, promote abstraction, and improve code readability.

### Example:
```python
def greet(name):
    print("Hello, " + name)

greet("Alice")  # Output: Hello, Alice
```
## Turtle Loop:

### Overview:
In turtle graphics, a loop can be used to repeat a series of drawing commands. This allows for the creation of complex shapes and patterns by iteratively drawing smaller components.

### Commentary:
Using loops in turtle graphics can simplify the drawing process, especially when creating repetitive patterns or shapes. Loops can be combined with other turtle commands to create intricate designs.

### Example:
```python
import turtle

# Create turtle object
t = turtle.Turtle()

# Draw a square using a loop
for _ in range(4):
    t.forward(100)
    t.left(90)

# Keep the window open
turtle.mainloop() ```
