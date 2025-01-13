# Python literals

A literal is data whose values are determined by the literal itself.

## Objective

1. Understand how Python uses literals.
2. Differentiate Integer, Float, Boolean and String data types.
3. Understanding how arithmetic operations are performed and recognizing the precedence of operators.

## Prerequisite

- Python & literals lecture

## What do you need to complete this exercise?

- You can perform this exercise in any Python IDE, including JupyterLab or Google Colab. I recommend using PyCharm by JetBrains. As a Miramar College student, you are eligible for a free license for the JetBrains IDE environment. Please follow my video tutorial on how to download and install PyCharm Professional. 

### 1. Literals

What will the output be without using Python? Aim for 80% accuracy.

```python
print(5 + 2 - 2)
# ______________________
print(5 / 2)
# ______________________
print(6 // 2) # // integer division
# ______________________
print(2. * 3)
# ______________________
print(2 < 4)
# ______________________
print(2 >= 2)
# ______________________
print("Hello"+"World")
# ______________________
print("bla" * 3)
# ______________________
print(2 * 3 ** 3)
# ______________________
print(5 * 25 // 13 + 100 / 2 % 13 // 2)
# ______________________
print(2 * 3 % 5)
# ______________________
print((2 % -4), (2 % 4), (2 ** 3 ** 2))
# ______________________
```

Please verify using Python to determine if you have achieved at least 80% correct answers.

### 2. Data type

What will the output be without using Python? Aim for 80% accuracy.

```python
type("Hello")
# ______________________
type(1+"2")
# ______________________
type(1.)
# ______________________
type('A')
# ______________________
type(500)
# ______________________
type(True)
# ______________________
type("False")
# ______________________
```

Please verify using Python to determine if you have achieved at least 80% correct answers.

### 3. Operator precedence

a) Write your arithmetic expression that uses at least one operator from each group and prove the operator's precedence. For example ```5 * 25 % 13 + 100 / -2 * 13 // 2 ** 3```

b) What will the output be without using Python after writing your arithmetic expression? Use the table below for your reference.

c) Please verify using Python to determine if you have done it correctly.

| Priority | Operator                                                     | Notes                    |
| :------- | :----------------------------------------------------------- | :----------------------- |
| 1        | `**`                                                         | Right to left evaluation |
| 2        | `+`, `-` (note: unary operators located next to the right of the power operator bind more strongly) | unary                    |
| 3        | `*`, `/`, `//`, `%`                                          | Left to right evaluation |
| 4        | `+`, `-`                                                     | binary                   |

## Challenges

Please describe the challenges you faced during the exercise.

```python

# _________________________________________________________________________________________________

# _________________________________________________________________________________________________

# _________________________________________________________________________________________________

# _________________________________________________________________________________________________

# _________________________________________________________________________________________________

# _________________________________________________________________________________________________

```

**End of exercise**

