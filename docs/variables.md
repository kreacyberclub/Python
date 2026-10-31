# Variables

A variable in python is something stores a value or a data type, in layman terms. For those interested in the more precise, technical term, a variable is a named pointer that refers or points to a specific value stored in your computer's memory address. 

Now how do we store our data type in variables? We simply assign a data type to our variable.

`my_variable = 15`

In python `=` sign is referred to as the assignment operator, where we assign a data type to a variable. In this case, our variable is `my_variable` and the data stored is `15`. 

Try assigning variables to these data types : 

```py
12
34.123
"Hello, Everyone"
2 + 5j

```
There are also rules for naming variables and few important rules are : 

1. A variable must start with a letter or underscore, it can not start with numbers. For example `1my_variable` is not a valid name. You will get a syntax error, if you try it.

2. A variable must not contain spaces, instead of spaces, you can use underscores. For example `my variable` isn't valid but `my_variable` is valid.

3. A variable can not contain any symbols like (!, @, #, etc...) except underscores. For example, `my_variable!` is not a valid one.

4. A variable should not be inbuilt python function names like print, input, str, float etc... You can not assign a variable `int = 43`. This won't throw an error immediately, but it will break the rest of your program.

## Multiple variables

You can also assign multiple variables to multiple data types. For example, writing,

```py
name,age,city = "Alice", 19, "California"
```
is perfectly valid and equivalent to writing: 

```py
name = "Alice"
age  = 19
city = "California"

```

## Output variables

How do you output the value stored in a variable? You simply use the `print()` command on the variable. For example, if you want to see the value stored in age, you do `print(age)` and you will get 19.

Now try creating three variables called `university, trimester and courses` and assign some values to them. Then try printing out each of the variables. 

## Variables arithmetic

We saw how to perform arithmetic with numbers directly in the previous section. Alternatively, you could assign a number to a variable and then perform arithmetic on the variables. Here's a quick example : 

```py
a = 10
b = 7

print(a + b)
# Output: 17

print(a * b)
#Output: 70
```

You can also assign a variable to an input function. For example : 

```py
a = int(input("Enter number 1: "))
b = int(input("Enter number 2: "))

print(a - b)
```

Boom! You just made a simple calculator that can do subtraction by taking in user inputs. You can change the `int()` to `float()` if you also want to floating point operations. 

## Exercise 

Build your own calculator that takes two numbers as input from the users and adds and multiplies the two numbers and return their output by printing them.

## Solution

```py
a = int(input("Enter the first number: " ))
b = int(input("Enter the second number: " ))

print("Addition result is :", a+b)
print("Multiplication result is:", a * b)
```
