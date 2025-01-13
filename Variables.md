# Programming variables

Variables are human-friendly names of memory locations

## Objective

1. Understand how Python uses literals.
2. Differentiate Integer, Float, Boolean and String data types.
3. Understanding how arithmetic operations are performed and recognizing the precedence of operators.

## Prerequisite

- Programming variables

## What do you need to complete this exercise?

You can perform this exercise in any Python IDE, including JupyterLab or Google Colab.
I recommend using PyCharm by JetBrains. As a Miramar College student, you are eligible for a free license for the JetBrains IDE environment. 
Please follow my video tutorial on how to download and install PyCharm Professional. 

### 1. Variable definition
No need to declare the variable data type; variables can be assigned values or strings as needed.

```python
var1 = 10 # integer
print(type(var1)) # var1 holds integer data type
var2 = 100.0 # float
print(type(var2))  # var2 holds float data type
print(var1 * var2)  # var1 * var2 - float data type
str1 = "Hello World"
type(str1)
print(str1)
str2 = 'Single quote can also be used'
type(str2)
print(str2)
var1 = "Now I am a string data type"
del(var1) # delete the var1
```

### 2. Variable memory usage

```python
var1 = 10
# Check the memory address of ```var1``` by using the following statement
print(hex(id(var1)))
# __________________________________ Write down the address here
var1 = 100
# Check the memory address of ```var1``` again
print(hex(id(var1)))
# __________________________________ Write down the address here
```
You should see two different addresses of var1. Please explain why there are two distinct addresses. What happened to the first address?

```
# ________________________________________________________________________

# ________________________________________________________________________

# ________________________________________________________________________

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

