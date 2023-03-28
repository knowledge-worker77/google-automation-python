## Loops
Loops are used to write code that you want to be repeated over a certain time period or when a certain action is performed. Like, you can set a timer that sends a notification to you every 45 mins to take a break from your computer or when you close an app to remind you that you have closed the app.

## While loops
While loops work similar to nested if statements, they will keep continuously running your code until the desired condition is met. The only difference is that the code can be executed multiple times.

While loops can be used to ask for information from users and until they provide the right information the code will keep on asking them. Providing the correct variables and values is important when creating loops, if something goes wrong you might get stuck in an infinite loop.

For example if we write a loop that asks the user for a variable and then divides it by two and we pass it a zero then the condition wouldn't be completed because zero isn't divisible so the code will keep on running in an endless loop and it will waste your resources.

``` py
  x = 1
  while x < 5:
   print(x)
   x +=1
  ```

## For loop
The for-loop is used for iterating over a collection of values like an array or a dictionary. The simplest example of the for-loop would be to ask a user a number and then count to that number. 

```python
fruits = ["apple", "peach","mango"]
   for x in fruits:
     print(x)
```

For loops can also be nested like if statements so that you can iterate over sequence of numbers or values specifically.

## Recursion
Recursion is the repeated process of the same code to a smaller problem. It helps us reduce our complex problems into smaller ones. Recursion in programming happens when you tell a function to call itself, a recursive function will keep calling itself with a modified parameter until the required condition isn't met.

> Keep in mind, each programming language will have different values as to how many recursive calls that you can make. Python allows for only 1,000 recursive calls.