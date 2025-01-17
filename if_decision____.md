# Decision statements

To execute or not to execute—that is the question. I have adapted a Shakespeare quote, originally written as "To be, or not to be—that is the question." Decision statements generally work in a similar way. You evaluate an expression, and if the result is true, you perform a specific action; otherwise, you take a different action.

## Objective

1. Understand how decision statements are applied in Python
2. Skilled in troubleshooting techniques.

## Prerequisite

- Input functions
- Python literals
- Programming variables

## What do you need to complete this exercise?

You can perform this exercise in any Python IDE, including JupyterLab or Google Colab.
I recommend using PyCharm by JetBrains. As a Miramar College student, you are eligible for a free license for the JetBrains IDE environment. 
Please follow my video tutorial on how to download and install PyCharm Professional. 

### 1. Comparison operators
Decision statements utilize comparison operators, and based on the True or False result, specific statements are executed.

```python
print(2 < 5)  # this gives True
print(10 <= 10)  # this gives True
x = 10 
print(20 < x)  # this gives False
print("A" < "a")  # this gives True because the ASCII of "A" is 65 and "a" is 97. The Python interpreter converts the
# character in ASCII number and then compare.
print("Monday" > "Tuesday")  # this gives False because the first character of "Monday" (M) has a lower ASCII value
# as compared to the first character of "Tuesday" (T)
```

Research and find the ASCII number of all the characters available on the keyboard.

### 2. Decision statements

> Find the largest two integers

```python
# Read two numbers
number1 = int(input("Enter the first number: "))
number2 = int(input("Enter the second number: "))

# Choose the larger number
if (number1 > number2):
    larger_number = number1
else:
    larger_number = number2

# Print the result
print("The larger number is:", larger_number)

```

### 3. Problem-solving
a. Find the largest three integers just using ```if``` statements. Take user inputs and display the result. 

b. Find several approaches to identify an even or an odd number. The user will input an integer number and the output says "odd or even". Your code should have several sections of code separated by the comments. For example

```python
#######################
# Approach 1
#######################
# Approach 2
#######################
# Approach 3
#######################
```


### 4. Alternative code writeup
Revise the code using **nested** ```if```, ```elif```, and ```else``` statements, and add comments to clarify the logic.
```
name = input("What's your name? ")
time = int(input("What time is it? "))

if (time < 1200):
    print("Hi "+name + ", good morning!")
if (time < 1800):
    print("Hi "+name + ", good afternoon!")
if (time > 1800):
    print("Hi "+name + ", good evening!")

print("Good Bye")
```

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

  

**End of exercise**

