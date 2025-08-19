# Python variables

Variables are human-friendly names of memory locations

## Objective

1. Understand how to define variables in Python.
2. Gain a clear understanding of how the Python interpreter allocates memory addresses to variables.
3. Skilled in troubleshooting techniques.

## Prerequisite

- Python literals lecture & lab
- Programming variables lecture

## What do you need to complete this exercise?

- Please follow my video tutorial [installing Python and PyCharm CE on Windows](https://youtu.be/nFN0JW43GKY). Note: The version you see may differ slightly from what is shown in the video.
- Use the PyCharm IDE to write and compile your code. Submit your responses in a Markdown file on GitHub. Ensure that all code included in the Markdown file runs without errors. Refer to [Submitting Your Assignment Using GitHub](https://sdccd-edu.zoom.us/rec/share/F4rK6ZABMXlRn4aGlZ9P005e-iRKwq8rr9KuawDoJ77TdkybKU2tpf4l4QSe113g.ut4jpVaqaPY0oI7b?startTime=1725121532000) for detailed instructions.

### Variable definition

No need to declare the variable data type; variables can be assigned values or strings as needed.

```
<class 'int'>
<class 'float'>
1000.0
Hello World
Single quote can also be used
```

### Variable memory usage

```
var1 = 10
```

```
# Check the memory address of var1 by using the following statement
print(hex(id(var1)))
```

```
var1 = 100
# Check the memory address of var1 again
```

```
# Write your code here
```

You should see two distinct addresses for var1. Explain why there are two different addresses and what happened to the first one.

```
var2 = 100
# Write your print statement
# Check the memory address of var2. Did the Python interpreter assign a new memory address or reuse the existing one?
```

```
# Write your code here
```

### Memory map

```
str1 = "Hello"
str2 = "World"
```

```
# Find out the memory addresses of each character in str1 and str2.
# The following is the example
```

```
print(hex(id(str1[0])), hex(id(str1[1])))  # where 0 is the first index and 1 is the second index
# Use the same method as described above to find the addresses of additional characters and complete the table below.
```

| Address in hexadecimal | Char |
| ---------------------- | ---- |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |
| #                      |      |

### Problem-solving

Let the variable `x` be `dog` and the variable `y` be `cat`. Write the values returned by the following operations: **Try solving without writing in Python.**

- x + y
- "the " + x + " chases the " + y
- x * 4

Write your answer here

If `x = 50`. Use an assignment statement to increment the value of `x` by 1.

```
# Write your code here
```

### Troubleshooting

Please troubleshoot the following issue **without using Python**, and explain your reasoning.

a. `hello = "hello"`
b. `_var = 100`
c. `!var_1 = 200`
d. `print = "print me"`
e. `False = 0`



Write your answer here

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
