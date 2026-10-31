# Let's start with the basics of python

First go to [Google Colab](https://colab.research.google.com) and sign in using your google account. Then click on new notebook to start working.

Each box structures you see is called a `cell`. A huge advantage of working with notebooks is that you can run parts of a program instead of running everything at once. This is not super necessary now, but when you start working with local python especially for data analysis, you will find the advantages of notebooks over executing the entire file at once.

## Basic Functions

Python has basic inbuilt functions. When you want to display a text as a output you use the function `print("text")` and python will cleanly display the text as an output. 

Try printing out the text "Hello World" in your notebook. 

> Remember to put your text inside double quotes ("") while printing them.

The next basic function is the input function which is implemented by `input("text")`. This function takes an input from the user and returns it in the output column. The user input can be anything - numbers or texts.

Try asking the user to Enter something by using `input("Enter Something")` and enter some characters and see what happens!

> You put these functions arguments under paranthesis '()' 

## Arithmetic

Python can perform arithmetic calculations with numbers (there are some nuances for calculations with texts as well, but this section focuses on the arithmetic with numbers).

Just like a calculator if you want to add two numbers you use the `+` sign in python. For subtraction it's the `-` sign and for multiplication however it's the `*` sign (Shift + 8) and the division symbol is `/` sign. Here are some examples:

```py
1 + 1
15 - 3
4 - 10
6 * 3
9 / 3

```
Their outputs respcetively would be : 

```py
2
12
-6
18
3.0
```

You can check this yourself and try out some examples on your own!

What about exponentiation and other arithmetic functions?

In python exponentiation is implemented by the `**` sign (two asterisks). Therefore, 
`2 ** 3` will give you `8` (2 cubed 3). Python also has the modulus operator given by `%` and this gives the remainder value after dividing two values. For example, `12 % 5` will give you `2` as the remainder after division will be 2. Finally, we can also implement floor division using `//` (double slash). Floor division divides two numbers and rounds down to the nearest integer value instead of giving the answer in decimals. For example 
`12 // 5` will give `2` as `12 / 5` is `2.4` and it rounds down to the nearest integer which is `2`. Even `13 // 5` will give `2` as `13 / 5` is `2.6` but 2.6 rounded down to the nearest integer is `2`

Try out these examples yourself : 

```py
6 ** 5
20 % 8
18 // 7
```

## Basic Data Types

Python has various data types. Some include: 

1. Numeric
    - `int` Stands for integers, these numbers are positive or negative whole numbers. 
    - `float` Stands for real numbers, it can be decimals, whole numbers or integers.
    - `complex` Stands for complex numbers in the form `ai + bj`

2. Text
    - `string` Strings are the texts in python and is identified by either double ("") or single ('') quotes and is contained within them. Note that `"5"` is still a string as it is contained within quotes whereas `5` will be an integer.

3. Boolean
    - `bool` Stands for Boolean Logic to represent logical values and it only has `True` or `False`. The binary equivalent is `0` for False and `1` for True.

## Type Conversions

You can check the data type of a character using the `type` function. Try checking the types of:

```py
5
"Hello"
4 + 7j
False
```

A character can be converted into string by passing the `str()` function. This converts any character (integer, float, bool or complex to a string). Now try using the string function on `6 + 2j` and `True`.

A character can be converted into integer using the `int()` function and can be converted into a float using the `float()` function. See what happens when you do `float("45.45")` or `int("12")`. But notice what happens when you try doing `int("45.45")`. It throws an error. But what happens when you forcefully convert a float to an integer? It will be truncated and only show the integer value. Try `int(45.45)`. 

But converting non number, text strings like `"Hello"` or `"World"` to either float or integer will show an error.
Try applying the int and float functions on these strings and see the error that you get.

Boolean type conversion is pretty easy. If you have an integer or a float, and if you apply the `bool()` function to convert it, your result will either be True or False. If your number is zero it will return False, if your number is any other number other than 0, it will return True.

Similarly for strings, `bool("")` (Boolean type function for an empty string) will give you False, while any other string will give you True. 

Applying `int`,`float` or `str` functions on Boolean values (True or False) are pretty straightforward. True gives 1 in integer and 1.0 in floating point values, whereas False gives 0 in integer and 0.0 in floating point values. Whereas using the `str()` function on Boolean just returns `"True"` or `"False"`.

> Note that Boolean values in python have uppercase in the first letter and the rest are lowercase like True and False.
