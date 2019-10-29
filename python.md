# Python Getting Started
-----

Python is one of the easiest programming languages out there. It is great for beginners and allows you to do very powerful things as you continue to learn and expand your skillset.

To get started, first open https://repl.it/languages and choose Python as your language.

This is your editor and environment where you can write code, you can use THIS online tool or your own computer if you have Python installed.

To get started, you need to understand how the language operates.

## Exercise 1 

```py
print("Hello World")
```
Type this code into your editor and hit run, you'll notice the terminal outputs "Hello World"

**What does this do?** By writing this code, you are simply calling a "function" defined as ``print`` and telling it to *print* "Hello World". Functions will be discussed more later.

## Exercise 2 (Math)
Let's try using that print function to do some more complicated things, for example:
```py
print(3 * 3)
```
This statement multiplies 3 by 3 to get 9, and then prints that out in the terminal.

You can also do things like:
```py
print(3 + 3) # 6
print(3 - 3) # 0
print(3 / 3) # 1
print(3 % 2) # 1
```

The ``%`` "operator" is a special operator that takes the remainder of the number, so it divides (in the example above) 3 by 2, and returns the remainder (which is 1).

## Exericse 3 (Variables)
Variables are also things we can make, here is how:
```py
name = "James"
age = 14

print(name)
print(age)
```

In this example, if you edit the variables at the top, you will change what prints out from the last 2 statements.

## Exercise 4 (String Math)

Yes, you can do math with strings! Like adding them together!

```py
print("I am " + "happy")
```

Simple enough, you can add strings together, but technically the above statement is the same as ``print("I am happy")``, so how is this useful?

It's useful when you use variables. Remember our example from the previous exercise? Now we can do this:

```py
name = "James"
age = 14

print("Hi, I am " + name + " and I am " + str(age) + " years old!") 
```

The only caveat in this example is since age is a number (14), you need to convert it into a string by using the ``str()`` function! We'll explore more about number conversions later.

## Exercise 5 (User Input)
```py
name = input("Enter your name: ")
age = input("Enter your age: ")

print("Hi I am " + name + " and I am " + age + " years old!")
```

In this example, we are using the function ``input()`` to ask the user a question and then we are storing those values (from the user) in a variable and printing it out.

Try running it and entering your own values!

## Exercise 6 (Loops)
Sometimes, you need to have repeat the same task multiple times, for example, when you are building something to count to 10. In a case like this, you should use a for loop!

```py
for x in range(10):
    print(x) #0,1,2,3,4,5,6,7,8,9
```
In this example, we are defining a variable named ``x`` for every value inside the range of 0-9 (goes to 10, but does not include 10, and starts at 0) and then assigns that value to x.

For example, on the first run; it assigns 0 to x, on the second run, it assigns 1... and so forth.

For each of those assignments to x, it prints out the value to the terminal, therefore the output would be from 0 to 9.