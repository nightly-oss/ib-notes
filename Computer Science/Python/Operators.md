## Arithmetic Operators
These are used to do arithmetic operations, like addition, subtraction, division, etc.

| Operator | What it does                  | Example      |
| -------- | ----------------------------- | ------------ |
| `+`      | Addition                      | `1 + 1 = 2`  |
| `-`      | Subtraction                   | `1 - 1 = 0`  |
| `*`      | Multiplication                | `2 * 2 = 4`  |
| `/`      | Division                      | `4 / 2 = 2`  |
| `//`     | Integer division              | `5 // 2 = 2` |
| `%`      | Gets the modulo of a division | `5 % 2 = 1`  |
| `**`     | Multiplies by a power of      | `5**2 = 25`  |

## Assignment Operations
Using **`=`**, you assign a value to a variable, like `x = 4`.
**You can add an operator before the `=` to assign a value relative to the variable.**
```python
x = 1    # x is now 1
x += 2   # x is now 3
x -= 1   # x is now 2
x *= 2   # x is now 4
x //= 2  # x is now 2
...
```

## Comparison Operators

| Operator | What it does             |
| -------- | ------------------------ |
| `>`      | greater than             |
| `<`      | smaller than             |
| `>=`     | greater than or equal to |
| `<=`     | smaller than or equal to |
| `==`     | is equal to              |
| `!=`     | is NOT equal to          |

You can also use logical operators like **`not`** (if the condition is NOT true), **`and`** (if BOTH conditions are true), and **`or`** (if one or the other is true) to expand a condition:
```python
if x >= 2 and x < 4:
	print("x is probably 3")
```

Use the **`is`** operator to check for the variable’s **type**:
```python
if x is int:
	print("x is a number")
```
You can also use **`is not`** for the opposite.

