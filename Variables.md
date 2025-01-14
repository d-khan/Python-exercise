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
# Check the memory address of var1 by using the following statement
print(hex(id(var1)))
# __________________________________ Write down the address here
var1 = 100
# Check the memory address of var1 again
print(hex(id(var1)))
# __________________________________ Write down the address here

# You should see two distinct addresses for var1. Explain why there are two different addresses and what happened to the first one.

# ________________________________________________________________________

# ________________________________________________________________________

# ________________________________________________________________________

var2 = 100
# Write your print statement
# Check the memory address of var2. Did the Python interpreter assign a new memory address or reuse the existing one?
# ________________________________________________________________________

# ________________________________________________________________________

```

### 3. Memory map

```python
str1 = "Hello"
str2 = "World"
# Find out the memory addresses of each character in str1 and str2.
# The following is the example
print(hex(id(str1[0])), hex(id(str1[1])))  # where 0 is the first index and 1 is the second index
# Perform the same way as mentioned above and find out the addresses of other characters.
```

| Address | Char |
| ------- | ---- |
| .       |      |
|         |      |
|         |      |
|         |      |
|         |      |
|         |      |
|         |      |
|         |      |
|         |      |




**End of exercise**

