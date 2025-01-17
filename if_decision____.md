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

b. Identify multiple methods to determine if a number is even or odd. The user will input an integer, and the output will indicate whether it's "odd" or "even." The code should be organized into sections, with comments separating each part. For example

```python
#######################
# Approach 1
#######################
# Approach 2
#######################
# Approach 3
#######################
```
c. Write the code to implement CISC 179 course "Grading Scheme". The following is the grading scheme.
|Grade|Percent|Description
|-|-----|-|
|A|>90|Work of genuinely superior quality.|
|B|80-89|Passing performance falls approximately in the upper distribution of passing grades.|
|C|71-79|Passing performance falls approximately in the center of the distribution of all passing grades.|
|D|65-70|Passing performance falls approximately in the lower distribution of passing grades.|
|F|<65|Failing performance that does not satisfy the basic requirements of the course and needs to be improved in significant ways.|

The user input the percentage in integer and the output shows the grade and the description. Use ```if```, ```elif```, and ```else``` statements, and add comments to clarify the logic.


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

