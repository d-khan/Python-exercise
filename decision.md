# Decision statements

To execute or not to execute—that is the question. I have adapted a Shakespeare quote, originally written as "To be, or not to be—that is the question." Decision statements generally work in a similar way. You evaluate an expression, and if the result is true, you perform a specific action; otherwise, you take a different action.

## Objective

1. Understand how decision statements are applied in Python
2. Apply comparison, logical and bitwise logical operators to evaluate the expression

## Prerequisite

- Converting binary to decimal and decimal to binary
- Decision statements
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

Research and find the ASCII number of all the characters available on the keyboard using Python.

### 2. Logical operators (and, or, not)
**Do not write logical operators in all uppercase like AND, OR, NOT - Syntax Error**

**and logical operator:** Both expression's result need to be True to get the True output. 
If one expression's result is False, the output will be False regardless of the second expression's result. For example,

``` python
10 > 4 and 50 < 100  # True and True is True
10 < 4 and 50 < 100  # Here first expression is False, the output will be False
```
**or logical operator:** Both expression's result need to be False to get the False output. 
If one expression's result is True, the output will be True regardless of the second expression's result. For example,

``` python
10 < 4 or 50 > 100  # False and False is False
10 > 4 and 50 > 100  # Here first expression is True, the output will be True
```
**not logical operator:** Inverts the result
```python
10 > 4 # this is True
not(10 > 4) # this is False
```

### 3. Bitwise logical operators (and, or, not, xor)
**Remember bitwise logical operators operates on bits**
To differentiate between logical operators and bitwise logical operators, Python uses distinct symbols for each.

| Name of the logical operator | Logical operator in Python | Bitwise logical operator in Python |
| ---------------------------- | -------------------------- | ---------------------------------- |
| and                          | and                        | &                                  |
| or                           | or                         | \|                                 |
| not                          | not                        | ~                                  |
| xor                          | -                          | ^                                  |
|                              |                            |                                    |

#### Example bitwise or
```python
x = 0b1110 # 0b represents binary number, decimal 14
y = 0b1011 # decimal 11
result = x | y # Bitwise or, result in decimal format
print(result)
print(bin(result)) # bin() function converts decimal to binary

# Proof
# 1110
# 1011
# ----
# 1111
```

### 4. Decision statements

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

> Nested conditional statements

```python
x = 10

if x > 5:  # True
    if x == 6:  # False
        print("nested: x == 6")
    elif x == 10:  # True
        print("nested: x == 10")
    else:
        print("nested: else")
else:
    print("else")

```


### 5. Problem-solving
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
c. Implement the grading scheme for the CISC 179 course. The grading scheme as follows:
|Grade|Percent|Description
|-|-----|-|
|A|>90|Work of genuinely superior quality.|
|B|80-89|Passing performance falls approximately in the upper distribution of passing grades.|
|C|71-79|Passing performance falls approximately in the center of the distribution of all passing grades.|
|D|65-70|Passing performance falls approximately in the lower distribution of passing grades.|
|F|<65|Failing performance that does not satisfy the basic requirements of the course and needs to be improved in significant ways.|

The user inputs a percentage as an integer, and the output displays the corresponding grade along with a description. The logic uses ```if```, ```elif```, and ```else``` statements, with comments to clarify each part.

d. Write a code which takes ```and```, ```or```, ```not``` as an user input. Create a truth table by writing your expressions. Display the truth table using ```print()``` function. Research how the truth tables for logical operators are structured.

### 6. Code revision
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

### 7. Output verification
What will be the output of the code provided below **without using Python**?
```python
x = 1
y = 1.0
z = "1"

if x == y:
    print("one")
if y == int(z):
    print("two")
elif x == y:
    print("three")
else:
    print("four")
```
Please execute the code provided above in Python to confirm your result.

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

