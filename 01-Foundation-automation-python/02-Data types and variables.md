## Data types
Data types are what programming languages use to determine what type of data we are dealing with. Any words that we write are represented as strings in programming languages and numbers are represented with either numbers or integers and numbers with decimal points are called floats.

Each data type has its own predefined methods that make it easier to manipulate their type of data like performing arithmetic operations on integer or finding the length of a string can be done with in-built methods that programming languages have.

## Variables
A variable is like a box, it has a special keyword that defines it and it has a name and can store anything you want in it. There are also a few things to keep in mind when creating variables.

You can't use the reserved keywords of a language as the name of your variable and the name must always start with a letter or underscore (in the case of Python) and not with a number and shouldn't contain any spaces or special characters.

## Functions
Functions are a crucial part of developing software and help us to minimize our code and make it reusable. Python already has many built-in functions like `print()` but you can also make your own functions and make them perform whatever task that you want.

In python we use the `def` keyword to define a function followed by the name of the function and then we add parentheses if we want to pass arguments in it. Most programming languages use a pair of curly braces after the parentheses to define the body of a function but in Python we use a colon and then write the body of the 
function from the next line.

``` py
  def HelloWorld():
      print("Hello world!")
  ```
  
>A function can also be used to calculate and return values:

```py
def Addition(a,b):
      add_result = a + b
      return add_result
  a =3
  b =5
  print(Addition(a,b))
  ```

## Conditionals
Conditionals are blocks of code that only run when their required conditions are true in your program. These are also used when you need to compare values like checking if the email address is already used or not and etc.

```py
  Age = 18
  if(Age >= 18):
      print("You are old enough to create an account")
  else:
      print("You must be 18 years or older to create an account")
  ```

