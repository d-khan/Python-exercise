# Dictionary in Python

In Python, a dictionary is a built-in data structure that stores data in key-value pairs. It is an unordered, mutable (changeable) collection, where each key must be unique and immutable (e.g., string, number, or tuple), while the value can be of any data type.

## Objective

- Understand how to create dictionary in Python
- Apply various methods on a dictionary
- Troubleshoot dictionary

## Prerequisite

- Lists & tuples
- Decision and loops
- Input functions

## What do you need to complete this exercise?

- Please follow my video tutorial [installing Python and PyCharm CE on Windows](https://youtu.be/nFN0JW43GKY). Note: The version you see may differ slightly from what is shown in the video.
- Use the PyCharm IDE to write and compile your code. Submit your responses in a Markdown file on GitHub. Ensure that all code included in the Markdown file runs without errors. Refer to [Submitting Your Assignment Using GitHub](https://sdccd-edu.zoom.us/rec/share/F4rK6ZABMXlRn4aGlZ9P005e-iRKwq8rr9KuawDoJ77TdkybKU2tpf4l4QSe113g.ut4jpVaqaPY0oI7b?startTime=1725121532000) for detailed instructions.

## 1. Creating and accessing dictionary

**1a)** Create dictionary of your choice of keys and values. Create dictionary size of 10 elements.

**1b.** Take inputs from a user and add them in a dictionary called `my_user_dict`

Here is the example of an user input:

SSN: 111-222-3333

Name: Steve Hawkins

The code continue to take user input and provide an option at the end of the user input; "Do you want to continue (Y/N)"

Identify how many keys you need to create a dictionary.

**Restrictions: Do not use functions and/or exceptions in this exercise**

```
# Write your code here.
```

**Converting tuples into a dictionary**

```
# List of tuples where each tuple represents a key-value pair

a = [("a", 1), ("b", 2), ("c", 3)]

# Convert the list of tuples into a dictionary

res = dict(a)

print(res)
```

```
{'a': 1, 'b': 2, 'c': 3}
```

**1c.** Based on the given tuple, create a code which checks for valid key & value pairs, and check for key duplication.

The code should provide assistance to a user to correct the error. For key duplication, ask user to change the key

**Restrictions: Do not use functions and/or exceptions in this exercise**

```
[('Name', 'Sarah Connor'),
 ('Date of birth', '1 Jan 1980'),
 ('Address', '1000 Black Mountain Drive', 92126),
 ('Name', 'Jim Hawkins')]
```

**1d.** Convert the following list into a dictionary. Automate the process by using the loop.

**Restrictions: Do not use functions and/or exceptions in this exercise**

**1e.** Use the following text and count the number of words using dictionary. Remember The or the counts as 2.

**The tiger (Panthera tigris) is a large cat and a member of the genus Panthera native to Asia. It has a powerful, muscular body with a large head and paws, a long tail and orange fur with black, mostly vertical stripes. It is traditionally classified into nine recent subspecies, though some recognise only two subspecies, mainland Asian tigers and the island tigers of the Sunda Islands.**

## 2. Troubleshooting

```
d_orig = {123:"Coconut"}
d_copy = d_orig
print(d_orig)
print(d_copy)
```

```
{123: 'Coconut'}
{123: 'Coconut'}
```

**2a.** Change the content of `d_copy` and make sure the content does not affect the `d_orig` dictionary. Verify using the code.

```
# Write your code here
```

**2b.** If it changes the content of the original dictionary, then propose how can you solve this problem.

```
# Write your code here
```

**2c.** Write a code that generates the following error and explain why there is such an error.

```
TypeError: unhashable type: 'list'
```

```
# Write your code here
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

