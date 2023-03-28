## Strings
Strings are a data type in most programming languages that allow us to manipulate alphabetic data. The details you give when you submit an online form are stored as strings unless they are phone numbers or any data that is numeric. 

Strings are written between quotes and any data written between the two quotes will be considered a string.

You can also use indexing on strings to manipulate them like you would with arrays. You can slice a really big string into a shorter one, find the length of it, change other data types to strings, searching through them, and formatting them. There are multiple ways to manipulate strings in Python and other programming languages as well.

 ```python
   name = "Harry oswald"
  ```

## Lists
Lists are a data type in python that allow us to work with collections of data like the list of all of the names of your friends or if you're monitoring the size of the network packets your device is receiving and sending.

```python
  list_of_fruits = ["apple","mango","peach"]
  ```

Lists are mutable so you can add or remove items from them dynamically and have their own methods like append, push, and pop that makes manipulating them easier.

The opposite of the list data type is the tuple, it is mostly similar to lists but is immutable meaning that we can't modify the items of the tuple dynamically. It is useful in situations where we don't want the contents of our collection to be changed.

```python
  list_of_people = ("Jack","Harry","Harold")
```

## Dictionaries
Dictionaries are used to organize values into collections they are like lists but you can't access the data inside of them using indexes. Dictionaries use a key-value pair architecture to access their values.

Dictionaries are also mutable so you can add, remove or change their values at any time.

```python
list_of_fruits = {"Apple": 10, "Mango": 3, "Peach": 5}
print(list_of_fruits)
```

Since a single key can only be added once, dictionaries are a great tool for counting elements and analyzing frequency. 

## Dictionaries vs. Lists
Lists are a great data structure in python for storing and collecting data that aren't required to be in a sequence or a particular order. If you need to collect data in a particular order or against a value then a dictionary is what you should choose.

Dictionaries also make searching through large files faster than lists as you can access the required value through its key instead of searching through the whole list.
