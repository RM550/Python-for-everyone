# 🐍 Understanding Variables and Data Types in Python

In Python, **variables** are used to store data, and **data types** define the kind of data stored in those variables. This guide explains everything in detail, from declaring variables to understanding different data types. 🚀

---

## ✅ What is a Variable?
A **variable** in Python is like a container that holds a value. Unlike other programming languages, you don’t need to declare the type of a variable explicitly—Python automatically assigns the type based on the value assigned.

### 📌 Variable Declaration
You can create a variable by assigning a value to a name:
```python
x = 10  # Integer variable
name = "Alice"  # String variable
is_python_fun = True  # Boolean variable
```
Python follows these rules for naming variables:
- ✅ Can contain letters (`a-z`, `A-Z`), digits (`0-9`), and underscores (`_`).
- ✅ Must **start** with a letter or underscore (`_`), not a number.
- ❌ Cannot use Python keywords (like `if`, `while`, `class`, etc.).
- ✅ Case-sensitive (`Name` and `name` are different variables).

---

## 🔢 Data Types in Python
Python has several built-in **data types**. Here are the most common ones:

### 1️⃣ **Integer (`int`)**
Integers are whole numbers (positive or negative) without decimals.
```python
age = 25  # Integer
```
🔹 To check the type:
```python
print(type(age))  # Output: <class 'int'>
```

### 2️⃣ **Floating Point (`float`)**
Floats are numbers with decimal points.
```python
price = 19.99  # Float
```
🔹 Example:
```python
print(type(price))  # Output: <class 'float'>
```

### 3️⃣ **String (`str`)**
Strings represent text and are enclosed in quotes (`'` or `"`).
```python
name = "Alice"  # String
message = 'Hello, World!'
```
🔹 Example:
```python
print(type(name))  # Output: <class 'str'>
```

### 4️⃣ **Boolean (`bool`)**
Booleans represent **True** or **False** values.
```python
is_sunny = True  # Boolean
is_raining = False
```
🔹 Example:
```python
print(type(is_sunny))  # Output: <class 'bool'>
```

### 5️⃣ **List (`list`)**
Lists store multiple values in one variable and are defined using square brackets `[]`.
```python
fruits = ["Apple", "Banana", "Cherry"]
```
🔹 Example:
```python
print(type(fruits))  # Output: <class 'list'>
```

### 6️⃣ **Tuple (`tuple`)**
Tuples are like lists but **cannot be modified (immutable)**.
```python
coordinates = (10, 20)
```
🔹 Example:
```python
print(type(coordinates))  # Output: <class 'tuple'>
```

### 7️⃣ **Dictionary (`dict`)**
Dictionaries store key-value pairs inside `{}`.
```python
person = {"name": "Alice", "age": 25}
```
🔹 Example:
```python
print(type(person))  # Output: <class 'dict'>
```

---

## 🔄 Type Conversion (Casting)
You can **convert** between data types using type casting functions.
```python
x = 5   # Integer
y = 3.14  # Float
z = "123"  # String

# Convert integer to float
print(float(x))  # Output: 5.0

# Convert float to integer
print(int(y))  # Output: 3

# Convert string to integer
print(int(z))  # Output: 123
```

---

## 🛠 Best Practices for Variables
✅ Use **meaningful** variable names:
```python
x = 25  # ❌ Bad name
age = 25  # ✅ Good name
```
✅ Use **snake_case** for variables:
```python
user_name = "Alice"  # ✅ Good practice
```
✅ Constants (unchangeable values) should be in **UPPERCASE**:
```python
PI = 3.14159  # Constant value
```

---

## 🎯 Conclusion
You now understand **variables** and **data types** in Python! 🎉

Happy Coding! 💻🐍

