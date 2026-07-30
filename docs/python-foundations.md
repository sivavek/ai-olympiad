# Python foundations

These are clean original notes intended to replace corrupted examples in the extracted text. Run every example in Python 3.

## Core syntax

```python
name = input("Name: ")
age = int(input("Age: "))
print(name, age)
```

`input()` returns text. Convert it with `int()` or `float()` when arithmetic is required.

Common types: `int`, `float`, `str`, and `bool`.

## Operators and precedence

```python
a, b = 10, 3
print(a + b)   # 13
print(a / b)   # decimal division
print(a // b)  # floor division
print(a % b)   # remainder
print(a ** 2)  # power
```

Multiplication, division, floor division, remainder, and powers are evaluated before addition and subtraction. Use parentheses when the intended order is important.

## Conditions

```python
score = 72
if score >= 80:
    result = "excellent"
elif score >= 50:
    result = "pass"
else:
    result = "practise more"
print(result)
```

Use `and` when both conditions must be true, `or` when either may be true, and `not` to reverse a Boolean value. Python uses `==` for comparison and `=` for assignment.

## Loops

```python
total = 0
for number in range(1, 6):
    total += number
print(total)  # 15
```

`range(1, 6)` produces 1 through 5. A `while` loop must change something that will eventually make its condition false.

## Collections

```python
colours = ["red", "blue"]       # mutable list
point = (3, 4)                    # tuple
unique = {"red", "blue", "red"}  # set: duplicates removed
student = {"name": "Maya", "score": 90}
```

Lists and strings use zero-based indexing. A negative index counts from the end. Dictionaries map keys to values.

## Functions

```python
def is_even(number):
    return number % 2 == 0

print(is_even(14))  # True
```

Trace arguments, local variables, return values, and the order of calls. Common MCQ traps include operator precedence, mutation of lists, aliasing, and the difference between `print()` and `return`.

## Code-reading checklist

- Check indentation and the exact spelling of names.
- Identify the type of each value after every assignment.
- Trace loops one iteration at a time.
- Watch for inclusive/exclusive bounds in `range` and slicing.
- Evaluate comparisons before combining them with `and` or `or`.
- Predict the output before running the code.
