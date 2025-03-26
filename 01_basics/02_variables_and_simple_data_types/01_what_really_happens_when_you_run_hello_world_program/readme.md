# Understanding What Happens When You Run `hello_world.py` 🚀

## Introduction
When you run a Python script like `hello_world.py`, a series of processes occur behind the scenes. This document explains in detail what happens when you execute `hello_world.py`, particularly focusing on variables and their usage. 

---

## What Happens When You Run `hello_world.py`? 🖥️

Assume `hello_world.py` contains the following code:
```python
print("Hello, World!")
```
When you execute `hello_world.py` using the Python interpreter (e.g., `python hello_world.py`), the following steps take place:

1. **Python Interpreter Starts** 🏁: The Python runtime environment is loaded into memory.
2. **Script is Read** 📜: Python reads the `hello_world.py` file and interprets the code line by line.
3. **Code Execution** ⚡:
   - The `print()` function is encountered.
   - The string `"Hello, World!"` is passed as an argument to `print()`.
   - `print()` sends the string to the standard output (usually the terminal), displaying `Hello, World!`.
4. **Program Terminates** 🔚: Once all instructions are executed, the script ends.

This process happens in milliseconds, making Python highly efficient for executing scripts.

---

## Variables in Python 🏷️

Variables in Python are used to store and manipulate data. Let's break it down into key concepts.

### 1. Naming and Using Variables ✍️
A variable is a named reference to a value stored in memory. You can define and use variables like this:

```python
greeting = "Hello, World!"
print(greeting)
```

- Here, `greeting` is a variable storing the string `"Hello, World!"`.
- When `print(greeting)` is executed, Python retrieves the value stored in `greeting` and prints it.

### Rules for Naming Variables:
- Must start with a letter (a-z, A-Z) or an underscore `_`.
- Cannot start with a number.
- Can contain letters, numbers, and underscores.
- Cannot use Python keywords (e.g., `print`, `def`, `class`, `if`).

Valid examples:
```python
name = "Reyan"
age = 16
_is_active = True
```
Invalid examples:
```python
2name = "Invalid"  # Starts with a number
class = "Python"   # Uses a reserved keyword
```

Additional Example:
```python
favorite_color = "Blue"
print("My favorite color is", favorite_color)
```

---

### 2. Avoiding Name Errors When Using Variables ⚠️
A common mistake in Python is using a variable before defining it, leading to a `NameError`.

#### Example of a `NameError`:
```python
print(message)  # message is not defined yet
message = "Hello"
```
**Solution:** Always define a variable before using it.
```python
message = "Hello"
print(message)
```

Python is case-sensitive, so `Message` and `message` are different variables.
```python
name = "Reyan"
print(Name)  # NameError: name 'Name' is not defined
```

Additional Example:
```python
username = "Sheru"
print("Welcome,", username)
```

---

### 3. Variables Are Labels 🏷️
Unlike languages like C or Java, Python variables do not store data directly; they act as **labels** pointing to data in memory.

```python
x = 5
y = x
```
- Here, `x` points to the value `5`.
- When we assign `y = x`, `y` now also points to the same value `5` (not a separate copy).
- If we later change `x`, it does **not** affect `y`.

Example:
```python
x = 10
y = x
x = 20
print(y)  # Output: 10
```
This concept is important when working with **mutable** data types like lists.

```python
list1 = [1, 2, 3]
list2 = list1
list1.append(4)
print(list2)  # Output: [1, 2, 3, 4]
```
Both `list1` and `list2` point to the same list in memory.

Additional Example:
```python
num1 = 42
num2 = num1
print("Before changing num1:", num2)
num1 = 99
print("After changing num1:", num2)  # num2 remains 42
```

---

## Conclusion 🎯
Understanding how Python executes a script and manages variables is fundamental for writing efficient code. Key takeaways:
- The Python interpreter reads and executes code line by line.
- Variables act as references to data in memory.
- Proper naming and initialization help avoid errors.

With this knowledge, you can now confidently write and debug Python scripts! 🚀

