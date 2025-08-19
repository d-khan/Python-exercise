# Python literals

A literal is data whose values are determined by the literal itself.

## Objective

1. Understand how Python uses literals.
2. Differentiate Integer, Float, Boolean and String data types.
3. Understanding how arithmetic operations are performed and recognizing the precedence of operators.

## Prerequisite

- Python & literals lecture

## What do you need to complete this exercise?

- Please follow my video tutorial [installing Python and PyCharm CE on Windows](https://youtu.be/nFN0JW43GKY). Note: The version you see may differ slightly from what is shown in the video.
- Use the PyCharm IDE to write and compile your code. Submit your responses in a Markdown file on GitHub. Ensure that all code included in the Markdown file runs without errors. Refer to [Submitting Your Assignment Using GitHub](https://sdccd-edu.zoom.us/rec/share/F4rK6ZABMXlRn4aGlZ9P005e-iRKwq8rr9KuawDoJ77TdkybKU2tpf4l4QSe113g.ut4jpVaqaPY0oI7b?startTime=1725121532000) for detailed instructions.

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

