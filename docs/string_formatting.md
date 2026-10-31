# String Formatting

## F Strings

In python F Strings are used to format statements inside your print statement. For example, in the previous section when I wanted to show addition and multiplication results, we did `print("Addition result is: ", a+b)` which prints our result in the end along with the text. Now what do I do if I want the calculation anywhere inside my print statement along with texts. That's when we use f-strings. For example : 

```py
a = 7
b = 10

print(f"If you add {a} and {b}, you get {a+b}")
```

You can also round off floats. For example, the following code block rounds to two decimal points.
```
x = 10 / 3
print(f"{x:.2f}")
```

You put a letter f with quotes and whichever values are not strings, i.e which are your variables that you want to show, you enclose them in curly brackets, along with other string characters.

## String methods

Python has a lot of inbuilt functions for strings. Let's look at some important ones : 

1. Lowercase
`"STRING".lower()` converts the entire string into lowercase characters.
Output : `"string"`

2. Uppercase
`"string".upper()` converts the entire string into uppercase characters.
Output : `"STRING"`

3. Capitalize
`"hello world".capitalize()` capitalizes the first letter of the first word in the sentence.
Output : `"Hello world"`

4. Title
`"hello world".title()` capitalizes the first letter of all the first words in the sentence.
Output : `"Hello World"`

5. Stripping
`"  Hello  ".strip()` removes all the empty white spaces before and after the word
Output : `"Hello"`

6. Replace
`"Monkeys like apples".replace("apples", "bananas")` replaces one word with another (first word inside the function with the second word)
Output : `"Monkeys like bananas"`

7. Count
`"Apples Apples Apples Oranges".count("Apples")` counts the number of occurences of the word specified in the function.
Output : `3` Apples appear 3 times

8. Length
`len("I love Krea University")` Returns the length of the entire string including spaces
Output : `22`

## Comments

Comments in python are required when you need to write description or notes about how your code works, but you don't want the code executing. Therefore, you pass comments in every line using the hashtag (#) symbol. Anything in a line after a hash will be ignored by python but you can read them in your own codespace for your understanding.

Examples : 

```py
# This is a comment and will be ignored by Python
print("Hi")
```

Here only the print function will run and the text will be ignored.

In this case, python will throw an error because only the first line counts as a comment as it starts with a #.
