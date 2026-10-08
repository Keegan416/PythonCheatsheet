# PythonCheatsheet
# Python Variables and Input Cheatsheet

A quick guide to storing values and getting information from a user in Python.

## 1. Variables

A variable is a named place where Python stores a value. You can use the variable's name later to access that value.

```python
name = "Bob"
age = 16
temperature = 72.5
is_student = True
```

| Variable | Type | What it contains |
|---|---|---|
| `name` | `str` | Text |
| `age` | `int` | A whole number |
| `temperature` | `float` | A decimal number |
| `is_student` | `bool` | `True` or `False` |

This example stores a name, age, temperature, and student status.

## 2. Getting String Input

The `input()` function displays a prompt, waits for the user to type a response, and returns the response as a string by default.

```python
name = input("What is your name? ")
print(name)
```

The answer is stored in `name`, and then `print(name)` displays it.

## 3. Getting Number Input

The `input()` function always returns text, even when the text looks like a number. You need to convert the input when you want to use it as a number.

### Whole numbers with `int()`

```python
age = int(input("How old are you? "))
print(age)
```

The `int()` function converts the input text to a whole number.

### Decimal numbers with `float()`

```python
height = float(input("What is your height? "))
print(height)
```

The `float()` function converts the input text to a decimal number.

Use `int()` for whole numbers without a decimal part. Use `float()` for numbers that may include decimals.

## Quick Reference

| Python item | Meaning | Use it for |
|---|---|---|
| `str` | String | Text |
| `int` | Integer | A whole number |
| `float` | Floating-point number | A number that may include decimals |
| `bool` | Boolean | `True` or `False` |
| `input()` | Gets user input as text | A typed response |
| `int(input())` | Gets input and converts it to an integer | A whole-number response |
| `float(input())` | Gets input and converts it to a float | A decimal-number response |
