## 1. Introduction to OOP Concepts

### Main Materi

**Teori:**
Object-Oriented Programming (OOP) is a programming paradigm that uses "objects" to design and build applications. An object is an instance of a class, which can contain data (attributes) and methods (functions) to manipulate that data. The four main principles of OOP are:

1. **Encapsulation:** Bundling the data (attributes) and methods (functions) that operate on the data into a single unit (class) and restricting access to some of the object's components.
2. **Inheritance:** Creating a new class based on an existing class to promote code reuse.
3. **Polymorphism:** Allowing objects of different classes to be treated as objects of a common superclass. It enables a unified interface for different implementations.
4. **Abstraction:** Hiding the complex implementation details and showing only the essential features of the object.

**Example:**

```python
class Dog:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def bark(self):
        return f"{self.name} says woof!"

# Creating an object of the Dog class
my_dog = Dog("Buddy", 3)

# Accessing attributes and methods
print(my_dog.name)  # Output: Buddy
print(my_dog.age)   # Output: 3
print(my_dog.bark())  # Output: Buddy says woof!
```

**Explanation:**
In this example, we define a `Dog` class with an `__init__` method that initializes the object's attributes (`name` and `age`). The class also has a `bark` method that returns a string. We then create an instance of the `Dog` class named `my_dog` and access its attributes and methods.

### Exercise

**Questions/Exercises:**
1. Define a `Car` class with the attributes `make`, `model`, and `year`.
2. Add a method `info` to the `Car` class that returns a string with the car's details.
3. Create an object of the `Car` class and print its attributes and the result of the `info` method.

### Solution of Exercise

**Answers/Explanations:**

```python
class Car:
    def __init__(self, make, model, year):
        self.make = make
        self.model = model
        self.year = year

    def info(self):
        return f"{self.year} {self.make} {self.model}"

# Creating an object of the Car class
my_car = Car("Toyota", "Camry", 2021)

# Accessing attributes and methods
print(my_car.make)  # Output: Toyota
print(my_car.model)  # Output: Camry
print(my_car.year)  # Output: 2021
print(my_car.info())  # Output: 2021 Toyota Camry
```

**Explanation:**
In this solution, we define a `Car` class with an `__init__` method that initializes the object's attributes (`make`, `model`, and `year`). The class also has an `info` method that returns a string with the car's details. We then create an instance of the `Car` class named `my_car` and access its attributes and methods.
