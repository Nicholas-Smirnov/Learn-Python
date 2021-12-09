# Variables

### What Are Variables?

**Variables** are values that store objects inside of them. An example of how to use a variable is shown below.

```python
MySecretNum = 10
print(MySecretNum)
```

And this is the output

```
10
```

### So what is happening?

When we initialize or create a variable, we have a basic syntax on how to do so.

```python
VariableName = Value
```

The values can be any object type used in python. The VariableName can be anything, **as long as it does not have any spaces in it!**

### Working with Variables

We can also work with variables. Here is an example on how to do so.

```python
MyVariable = "Hello"
MyVariable = "World!"
print(MyVariable)
```
And the output
```
World!
```

Why is it not printing ```Hello World!```? This is because we **re-defined** the variable. This means that we changed the value of the variable, and this led to the old value being completely wiped from the program.

### Quick Mathematical Operations

You can also do mathematical operations in Python. You can add, subtract, multiply, divide, power, modulus, and more! The main ones are shown below.

| Type | Syntax | Example |
| ---- | ------ | ------- |
| Addition | a + b | 1 + 1 |
| Subtraction | a - b | 5 - 2 |
| Multiplication | a * b | 3 * 6 |
| Division | a / b | 9 / 3 |
| Power | a ** b | 2 ** 2 |
| Modulus | a % b | 5 % s |

### String Operations???

Did you know that you can add strings together? An example is shown below

```python
print("Hello " + "World!")
```
```
Hello World!
```

You can also multiple string???

Yes you can.

```python
print("Hello" * 5)
```
```
HelloHelloHelloHelloHello
```

### Variable Operations

Since you know that you can use mathematical operations, you can do operations with variables as well! (Or in other words, with their values).

Here is an example of a simple addition tool

```python
MyFirstNum = 1
MySecondNum = 2
MyAnswer = MyFirstNum + MySecondNum
print(MyAnswer)
```

And the output is 

```
3
```

In addition, you can add as many values as you want, not just two.

```python
MyFirstNum = 1
MySecondNum = 2
MyThirdNum = 3
MyFourthNum = 4
MyAnswer = MyFirstNum + MySecondNum + MyThirdNum + MyFourthNum
print(MyAnswer)
```
And you get
```
10
```
