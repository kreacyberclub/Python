# Conditionals

Let's say we want something to happen if some condition is met. We do this with `if` statements. For example, we can have a program to greet a user if their name is `Haresh`.

```py
name = input("What is your name: ")

if name == "Haresh":
    print("Hello Haresh!")
```

(Notice we use `==` instead of `=`). This is because `=` is meant for assigning values to variables and the language would get confused.

What if we want to tell people they're not Haresh? For that, we have `else` statements.
```py
name = input("What is your name: ")

if name == "Haresh":
    print("Hello Haresh!")
else:
    print("Who are you? Where is Haresh??")
```

