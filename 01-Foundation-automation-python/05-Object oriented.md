## Object oriented programming
Object oriented programming is a programming paradigm in which we work with classes and objects to model our code and include many concepts like inheritance and encapsulation that are similar to real life scenarios.

The whole point of OOP is to define a real world concept in a way that the computer can understand.

## Instance methods
Methods are functions that operate on the attributes of a specific instance of a class. When we call the append method on a list, we're adding an element to the end of that specific list and not to any other lists. 

When we call the lower method on the string, we're making the contents of that specific string lowercase.

Calling methods on objects executes functions that operate on attributes of a specific instance of the class. This means that calling a method on a list, for example, only modifies that instance of a list, and not all lists globally.

We can define methods within a class by creating functions inside the class definition. These instance methods can take a parameter called self which represents the instance the method is being executed on.

This will allow you to access attributes of the instance using dot notation, like self.name, which will access the name attribute of that specific instance of the class object. When you have variables that contain different values for different instances, these are called instance variables.

## Class constructor
The constructor of the class is the method that's called when you call the name of the class. It’s always named init.

Instead of creating classes with empty or default values, we can set these values when we create the instance. This ensures that we don't miss an important value and avoids a lot of unnecessary lines of code and we can accomplish this using the constructor method.

```python
>>> class Apple:
...     def __init__(self, color, flavor):
...         self.color = color
...         self.flavor = flavor
...     def __str__(self):
...         return "This apple is {} and its flavor is               {}".format(self.color, self.flavor)
...
```

## Inheritance 
The principle of inheritance let's a programmer build relationships between concepts and group them together. In particular, this allows us to reduce code duplication by generalizing our code.

Just like people have parents, grandparents, and so on,objects have an ancestry too.
We can have an animal class that acts as a parent class to three classes land, sea, and flying animals and then these classes can have their own child classes that are about different types of animals. 

## Composition
There can be similar classes that are related to each other but don't inherit anything. This is called composition, in composition one class makes use of code contained in another class. 

## Modules
Python has a huge library of modules that you can use for almost anything that you need to do. By default Python comes with a standard library that contains a lot of modules for us to work with.

A module is a set of functions and methods that is defined in another file and is separated from our code. When we need to work with it we can simply import the module into our code and all of the functions and methods will be available to use.

```python
import random
random.randint(1,10)
```
